Node: funcMRIQC (ReportsWorkflow (GenerateReport (utility)
==========================================================


 Hierarchy : workflow_enumerator.funcMRIQC.ReportsWorkflow.GenerateReport
 Exec ID : GenerateReport.a0


Original Inputs
---------------


* function_str : def individual_html(in_iqms, in_plots=None, api_id=None):
    from pathlib import Path
    import datetime
    from json import load
    from mriqc import logging, __version__ as ver
    from mriqc.utils.misc import BIDS_COMP
    from mriqc.reports import REPORT_TITLES
    from mriqc.reports.utils import iqms2html, read_report_snippet
    from mriqc.data import IndividualTemplate

    report_log = logging.getLogger('mriqc.report')

    def _get_details(in_iqms, modality):
        in_prov = in_iqms.pop('provenance', {})
        warn_dict = in_prov.pop('warnings', None)
        sett_dict = in_prov.pop('settings', None)

        wf_details = []
        if modality == 'bold':
            bold_exclude_index = in_iqms.get('dumb_trs')
            if bold_exclude_index is None:
                report_log.warning('Building bold report: no exclude index was found')
            elif bold_exclude_index > 0:
                msg = """\
<span class="problematic">Non-steady state (strong T1 contrast) has been detected in the \
first {} volumes</span>. They were excluded before generating any QC measures and plots."""
                wf_details.append(msg.format(bold_exclude_index))

            hmc_fsl = sett_dict.pop('hmc_fsl')
            if hmc_fsl is not None:
                msg = 'Framewise Displacement was computed using '
                if hmc_fsl:
                    msg += 'FSL <code>mcflirt</code>'
                else:
                    msg += 'AFNI <code>3dvolreg</code>'
                wf_details.append(msg)

            fd_thres = sett_dict.pop('fd_thres')
            if fd_thres is not None:
                wf_details.append(
                    'Framewise Displacement threshold was defined at %f mm' % fd_thres)
        elif modality in ('T1w', 'T2w'):
            if warn_dict.pop('small_air_mask', False):
                wf_details.append(
                    '<span class="problematic">Detected hat mask was too small</span>')

            if warn_dict.pop('large_rot_frame', False):
                wf_details.append(
                    '<span class="problematic">Detected a zero-filled frame, has the original '
                    'image been rotated?</span>')

        return in_prov, wf_details, sett_dict

    in_iqms = Path(in_iqms)
    with in_iqms.open() as jsonfile:
        iqms_dict = load(jsonfile)

    # Now, the in_iqms file should be correctly named
    out_file = str(Path(in_iqms.with_suffix(".html").name).resolve())

    # Extract and prune metadata
    metadata = iqms_dict.pop('bids_meta', None)
    mod = metadata.pop('modality', None)
    prov, wf_details, _ = _get_details(iqms_dict, mod)

    file_id = [metadata.pop(k, None)
               for k in list(BIDS_COMP.keys())]
    file_id = [comp for comp in file_id if comp is not None]

    if in_plots is None:
        in_plots = []
    else:
        if any(('melodic_reportlet' in k for k in in_plots)):
            REPORT_TITLES['bold'].insert(3, ('ICA components', 'ica-comps'))
        if any(('plot_spikes' in k for k in in_plots)):
            REPORT_TITLES['bold'].insert(3, ('Spikes', 'spikes'))

        in_plots = [(REPORT_TITLES[mod][i] + (read_report_snippet(v), ))
                    for i, v in enumerate(in_plots)]

    pred_qa = None  # metadata.pop('mriqc_pred', None)
    config = {
        'modality': mod,
        'dataset': metadata.pop('dataset', None),
        'bids_name': in_iqms.with_suffix("").name,
        'timestamp': datetime.datetime.now().strftime("%Y-%m-%d, %H:%M"),
        'version': ver,
        'imparams': iqms2html(iqms_dict, 'iqms-table'),
        'svg_files': in_plots,
        'workflow_details': wf_details,
        'webapi_url': prov.pop('webapi_url'),
        'webapi_port': prov.pop('webapi_port'),
        'provenance': iqms2html(prov, 'provenance-table'),
        'md5sum': prov['md5sum'],
        'metadata': iqms2html(metadata, 'metadata-table'),
        'pred_qa': pred_qa
    }

    if config['metadata'] is None:
        config['workflow_details'].append(
            '<span class="warning">File has no metadata</span> '
            '<span>(sidecar JSON file missing or empty)</span>')

    tpl = IndividualTemplate()
    tpl.generate_conf(config, out_file)

    report_log.info('Generated individual log (%s)', out_file)
    return out_file

* in_iqms : /mnt/scrap/repronim/data/ds000003-qc/sub-02/func/sub-02_task-rhymejudgment_bold.json
* in_plots : ['/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/PlotMosaicMean/plot_func_mean_mosaic1.svg', '/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/PlotMosaicSD/plot_func_stddev_mosaic2_stddev.svg', '/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/BigPlot/sub-02_task-rhymejudgment_bold_valid_volreg_fmriplot.svg']

Execution Inputs
----------------


* function_str : def individual_html(in_iqms, in_plots=None, api_id=None):
    from pathlib import Path
    import datetime
    from json import load
    from mriqc import logging, __version__ as ver
    from mriqc.utils.misc import BIDS_COMP
    from mriqc.reports import REPORT_TITLES
    from mriqc.reports.utils import iqms2html, read_report_snippet
    from mriqc.data import IndividualTemplate

    report_log = logging.getLogger('mriqc.report')

    def _get_details(in_iqms, modality):
        in_prov = in_iqms.pop('provenance', {})
        warn_dict = in_prov.pop('warnings', None)
        sett_dict = in_prov.pop('settings', None)

        wf_details = []
        if modality == 'bold':
            bold_exclude_index = in_iqms.get('dumb_trs')
            if bold_exclude_index is None:
                report_log.warning('Building bold report: no exclude index was found')
            elif bold_exclude_index > 0:
                msg = """\
<span class="problematic">Non-steady state (strong T1 contrast) has been detected in the \
first {} volumes</span>. They were excluded before generating any QC measures and plots."""
                wf_details.append(msg.format(bold_exclude_index))

            hmc_fsl = sett_dict.pop('hmc_fsl')
            if hmc_fsl is not None:
                msg = 'Framewise Displacement was computed using '
                if hmc_fsl:
                    msg += 'FSL <code>mcflirt</code>'
                else:
                    msg += 'AFNI <code>3dvolreg</code>'
                wf_details.append(msg)

            fd_thres = sett_dict.pop('fd_thres')
            if fd_thres is not None:
                wf_details.append(
                    'Framewise Displacement threshold was defined at %f mm' % fd_thres)
        elif modality in ('T1w', 'T2w'):
            if warn_dict.pop('small_air_mask', False):
                wf_details.append(
                    '<span class="problematic">Detected hat mask was too small</span>')

            if warn_dict.pop('large_rot_frame', False):
                wf_details.append(
                    '<span class="problematic">Detected a zero-filled frame, has the original '
                    'image been rotated?</span>')

        return in_prov, wf_details, sett_dict

    in_iqms = Path(in_iqms)
    with in_iqms.open() as jsonfile:
        iqms_dict = load(jsonfile)

    # Now, the in_iqms file should be correctly named
    out_file = str(Path(in_iqms.with_suffix(".html").name).resolve())

    # Extract and prune metadata
    metadata = iqms_dict.pop('bids_meta', None)
    mod = metadata.pop('modality', None)
    prov, wf_details, _ = _get_details(iqms_dict, mod)

    file_id = [metadata.pop(k, None)
               for k in list(BIDS_COMP.keys())]
    file_id = [comp for comp in file_id if comp is not None]

    if in_plots is None:
        in_plots = []
    else:
        if any(('melodic_reportlet' in k for k in in_plots)):
            REPORT_TITLES['bold'].insert(3, ('ICA components', 'ica-comps'))
        if any(('plot_spikes' in k for k in in_plots)):
            REPORT_TITLES['bold'].insert(3, ('Spikes', 'spikes'))

        in_plots = [(REPORT_TITLES[mod][i] + (read_report_snippet(v), ))
                    for i, v in enumerate(in_plots)]

    pred_qa = None  # metadata.pop('mriqc_pred', None)
    config = {
        'modality': mod,
        'dataset': metadata.pop('dataset', None),
        'bids_name': in_iqms.with_suffix("").name,
        'timestamp': datetime.datetime.now().strftime("%Y-%m-%d, %H:%M"),
        'version': ver,
        'imparams': iqms2html(iqms_dict, 'iqms-table'),
        'svg_files': in_plots,
        'workflow_details': wf_details,
        'webapi_url': prov.pop('webapi_url'),
        'webapi_port': prov.pop('webapi_port'),
        'provenance': iqms2html(prov, 'provenance-table'),
        'md5sum': prov['md5sum'],
        'metadata': iqms2html(metadata, 'metadata-table'),
        'pred_qa': pred_qa
    }

    if config['metadata'] is None:
        config['workflow_details'].append(
            '<span class="warning">File has no metadata</span> '
            '<span>(sidecar JSON file missing or empty)</span>')

    tpl = IndividualTemplate()
    tpl.generate_conf(config, out_file)

    report_log.info('Generated individual log (%s)', out_file)
    return out_file

* in_iqms : /mnt/scrap/repronim/data/ds000003-qc/sub-02/func/sub-02_task-rhymejudgment_bold.json
* in_plots : ['/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/PlotMosaicMean/plot_func_mean_mosaic1.svg', '/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/PlotMosaicSD/plot_func_stddev_mosaic2_stddev.svg', '/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/BigPlot/sub-02_task-rhymejudgment_bold_valid_volreg_fmriplot.svg']


Execution Outputs
-----------------


* out_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/GenerateReport/sub-02_task-rhymejudgment_bold.html


Runtime info
------------


* duration : 0.075275
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/GenerateReport


Environment
~~~~~~~~~~~


* AFNI_IMSAVE_WARNINGS : NO
* AFNI_MODELPATH : /opt/afni/models
* AFNI_PLUGINPATH : /opt/afni/plugins
* AFNI_TTATLAS_DATASET : /opt/afni/atlases
* ANTSPATH : /usr/lib/ants
* CPATH : /usr/local/miniconda/include/:
* DATALAD_CONTAINER_NAME : containers/bids-mriqc
* DISPLAY : :5996746
* FSLDIR : /usr/share/fsl/5.0
* FSLMULTIFILEQUIT : TRUE
* FSLOUTPUTTYPE : NIFTI_GZ
* FSLTCLSH : /usr/bin/tclsh
* FSLWISH : /usr/bin/wish
* HOME : /home/bidsapp
* LANG : en_US.UTF-8
* LC_ALL : en_US.UTF-8
* LD_LIBRARY_PATH : /usr/lib/fsl/5.0::/.singularity.d/libs
* MKL_NUM_THREADS : 1
* MKL_THREADING_LAYER : INTEL
* OMP_NUM_THREADS : 1
* PATH : /usr/local/miniconda/bin:/opt/afni:/usr/lib/ants:/usr/lib/fsl/5.0:/usr/lib/afni/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
* POSSUMDIR : /usr/share/fsl/5.0
* PS1 : Singularity> 
* PWD : /mnt/scrap/repronim/data/ds000003-qc
* PYTHONNOUSERSITE : 1
* SINGULARITY_CONTAINER : MD5E-s2914574367--827e2277cfe2e482546b18535ca18251.1.sing
* SINGULARITY_NAME : MD5E-s2914574367--827e2277cfe2e482546b18535ca18251.1.sing
* TERM : screen

