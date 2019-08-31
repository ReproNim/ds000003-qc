Node: funcMRIQC (ComputeIQMs (datasink (bids)
=============================================


 Hierarchy : workflow_enumerator.funcMRIQC.ComputeIQMs.datasink
 Exec ID : datasink.a1


Original Inputs
---------------


* _outputs : {'aqi': 0.013161508924050632, 'aor': 0.001280506329113924, 'gcor': 0.00475767, 'dummy_trs': 2}
* acq_id : <undefined>
* dataset : unknown
* in_file : /mnt/scrap/repronim/data/ds000003-qc/sourcedata/sub-13/func/sub-13_task-rhymejudgment_bold.nii.gz
* metadata : {'RepetitionTime': 2.0, 'TaskName': 'rhyme judgment'}
* modality : bold
* out_dir : /mnt/scrap/repronim/data/ds000003-qc
* provenance : {'md5sum': '7d779718aa1faa7ff3bfe8f44e8a51c1', 'settings': {'fd_thres': 0.2, 'hmc_fsl': False}, 'software': 'mriqc', 'version': '0.15.1', 'webapi_port': None, 'webapi_url': 'https://mriqc.nimh.nih.gov/api/v1'}
* rec_id : <undefined>
* root : {'dvars_nstd': 23.367136013757957, 'dvars_std': 1.0361529665605096, 'dvars_vstd': 0.9600425164331211, 'efc': 0.49440980684979424, 'fber': 2967.408935546875, 'fd_mean': 0.11034207874913458, 'fd_num': 17, 'fd_perc': 10.759493670886076, 'fwhm_avg': 2.701829033333333, 'fwhm_x': 2.613504, 'fwhm_y': 3.1714656000000003, 'fwhm_z': 2.3205175, 'gsr_x': -0.009504396468400955, 'gsr_y': 0.02730996161699295, 'size_t': 158, 'size_x': 64, 'size_y': 64, 'size_z': 33, 'snr': 4.890872415607783, 'spacing_tr': 2.0, 'spacing_x': 3.125, 'spacing_y': 3.125, 'spacing_z': 4.0, 'summary_bg_k': 107.39915219626609, 'summary_bg_mad': 4.241368770599365, 'summary_bg_mean': 23.642351150512695, 'summary_bg_median': 11.278481483459473, 'summary_bg_n': 77290.0, 'summary_bg_p05': 7.949367523193359, 'summary_bg_p95': 77.97816848754886, 'summary_bg_stdv': 44.32646560668945, 'summary_fg_k': 2.682573255422631, 'summary_fg_mad': 93.60102844238281, 'summary_fg_mean': 624.08349609375, 'summary_fg_median': 652.0189819335938, 'summary_fg_n': 27473.0, 'summary_fg_p05': 367.3329223632812, 'summary_fg_p95': 786.422802734375, 'summary_fg_stdv': 133.31100463867188, 'tsnr': 47.13072967529297}
* run_id : <undefined>
* session_id : <undefined>
* subject_id : 13
* task_id : rhymejudgment

Execution Inputs
----------------


* _outputs : {'aqi': 0.013161508924050632, 'aor': 0.001280506329113924, 'gcor': 0.00475767, 'dummy_trs': 2}
* acq_id : <undefined>
* dataset : unknown
* in_file : /mnt/scrap/repronim/data/ds000003-qc/sourcedata/sub-13/func/sub-13_task-rhymejudgment_bold.nii.gz
* metadata : {'RepetitionTime': 2.0, 'TaskName': 'rhyme judgment'}
* modality : bold
* out_dir : /mnt/scrap/repronim/data/ds000003-qc
* provenance : {'md5sum': '7d779718aa1faa7ff3bfe8f44e8a51c1', 'settings': {'fd_thres': 0.2, 'hmc_fsl': False}, 'software': 'mriqc', 'version': '0.15.1', 'webapi_port': None, 'webapi_url': 'https://mriqc.nimh.nih.gov/api/v1'}
* rec_id : <undefined>
* root : {'dvars_nstd': 23.367136013757957, 'dvars_std': 1.0361529665605096, 'dvars_vstd': 0.9600425164331211, 'efc': 0.49440980684979424, 'fber': 2967.408935546875, 'fd_mean': 0.11034207874913458, 'fd_num': 17, 'fd_perc': 10.759493670886076, 'fwhm_avg': 2.701829033333333, 'fwhm_x': 2.613504, 'fwhm_y': 3.1714656000000003, 'fwhm_z': 2.3205175, 'gsr_x': -0.009504396468400955, 'gsr_y': 0.02730996161699295, 'size_t': 158, 'size_x': 64, 'size_y': 64, 'size_z': 33, 'snr': 4.890872415607783, 'spacing_tr': 2.0, 'spacing_x': 3.125, 'spacing_y': 3.125, 'spacing_z': 4.0, 'summary_bg_k': 107.39915219626609, 'summary_bg_mad': 4.241368770599365, 'summary_bg_mean': 23.642351150512695, 'summary_bg_median': 11.278481483459473, 'summary_bg_n': 77290.0, 'summary_bg_p05': 7.949367523193359, 'summary_bg_p95': 77.97816848754886, 'summary_bg_stdv': 44.32646560668945, 'summary_fg_k': 2.682573255422631, 'summary_fg_mad': 93.60102844238281, 'summary_fg_mean': 624.08349609375, 'summary_fg_median': 652.0189819335938, 'summary_fg_n': 27473.0, 'summary_fg_p05': 367.3329223632812, 'summary_fg_p95': 786.422802734375, 'summary_fg_stdv': 133.31100463867188, 'tsnr': 47.13072967529297, 'aqi': 0.013161508924050632, 'aor': 0.001280506329113924, 'gcor': 0.00475767, 'dummy_trs': 2, 'bids_meta': {'subject_id': '13', 'task_id': 'rhymejudgment', 'modality': 'bold', 'RepetitionTime': 2.0, 'TaskName': 'rhyme judgment', 'dataset': 'unknown'}, 'provenance': {'md5sum': '7d779718aa1faa7ff3bfe8f44e8a51c1', 'settings': {'fd_thres': 0.2, 'hmc_fsl': False}, 'software': 'mriqc', 'version': '0.15.1', 'webapi_port': None, 'webapi_url': 'https://mriqc.nimh.nih.gov/api/v1'}}
* run_id : <undefined>
* session_id : <undefined>
* subject_id : 13
* task_id : rhymejudgment


Execution Outputs
-----------------


* out_file : /mnt/scrap/repronim/data/ds000003-qc/sub-13/func/sub-13_task-rhymejudgment_bold.json


Runtime info
------------


* duration : 0.001637
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/datasink


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

