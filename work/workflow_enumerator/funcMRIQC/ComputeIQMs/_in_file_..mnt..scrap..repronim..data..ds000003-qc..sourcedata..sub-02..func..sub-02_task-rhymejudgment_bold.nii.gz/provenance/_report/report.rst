Node: funcMRIQC (ComputeIQMs (provenance (utility)
==================================================


 Hierarchy : workflow_enumerator.funcMRIQC.ComputeIQMs.provenance
 Exec ID : provenance.a0


Original Inputs
---------------


* function_str : def _add_provenance(in_file, settings):
    from mriqc import __version__ as version
    from nipype.utils.filemanip import hash_infile
    out_prov = {
        'md5sum': hash_infile(in_file),
        'version': version,
        'software': 'mriqc',
        'webapi_url': settings.pop('webapi_url'),
        'webapi_port': settings.pop('webapi_port'),
    }

    if settings:
        out_prov['settings'] = settings

    return out_prov

* in_file : /mnt/scrap/repronim/data/ds000003-qc/sourcedata/sub-02/func/sub-02_task-rhymejudgment_bold.nii.gz
* settings : {'fd_thres': 0.2, 'hmc_fsl': False, 'webapi_url': 'https://mriqc.nimh.nih.gov/api/v1', 'webapi_port': None}

Execution Inputs
----------------


* function_str : def _add_provenance(in_file, settings):
    from mriqc import __version__ as version
    from nipype.utils.filemanip import hash_infile
    out_prov = {
        'md5sum': hash_infile(in_file),
        'version': version,
        'software': 'mriqc',
        'webapi_url': settings.pop('webapi_url'),
        'webapi_port': settings.pop('webapi_port'),
    }

    if settings:
        out_prov['settings'] = settings

    return out_prov

* in_file : /mnt/scrap/repronim/data/ds000003-qc/sourcedata/sub-02/func/sub-02_task-rhymejudgment_bold.nii.gz
* settings : {'fd_thres': 0.2, 'hmc_fsl': False}


Execution Outputs
-----------------


* out : {'md5sum': 'cb7d19f6eb96bf2b39afdac474a33ed7', 'settings': {'fd_thres': 0.2, 'hmc_fsl': False}, 'software': 'mriqc', 'version': '0.15.1', 'webapi_port': None, 'webapi_url': 'https://mriqc.nimh.nih.gov/api/v1'}


Runtime info
------------


* duration : 0.048841
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/provenance


Environment
~~~~~~~~~~~


* AFNI_IMSAVE_WARNINGS : NO
* AFNI_MODELPATH : /opt/afni/models
* AFNI_PLUGINPATH : /opt/afni/plugins
* AFNI_TTATLAS_DATASET : /opt/afni/atlases
* ANTSPATH : /usr/lib/ants
* CPATH : /usr/local/miniconda/include/:
* DATALAD_CONTAINER_NAME : containers/bids-mriqc
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
* OMP_NUM_THREADS : 1
* PATH : /usr/local/miniconda/bin:/opt/afni:/usr/lib/ants:/usr/lib/fsl/5.0:/usr/lib/afni/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
* POSSUMDIR : /usr/share/fsl/5.0
* PS1 : Singularity> 
* PWD : /mnt/scrap/repronim/data/ds000003-qc
* PYTHONNOUSERSITE : 1
* SINGULARITY_CONTAINER : MD5E-s2914574367--827e2277cfe2e482546b18535ca18251.1.sing
* SINGULARITY_NAME : MD5E-s2914574367--827e2277cfe2e482546b18535ca18251.1.sing
* TERM : screen

