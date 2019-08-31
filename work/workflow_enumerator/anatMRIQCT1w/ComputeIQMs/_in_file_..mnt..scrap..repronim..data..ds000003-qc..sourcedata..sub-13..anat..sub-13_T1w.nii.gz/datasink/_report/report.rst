Node: anatMRIQCT1w (ComputeIQMs (datasink (bids)
================================================


 Hierarchy : workflow_enumerator.anatMRIQCT1w.ComputeIQMs.datasink
 Exec ID : datasink.a1


Original Inputs
---------------


* _outputs : {'qi_2': 0.005237149922495059}
* acq_id : <undefined>
* dataset : unknown
* in_file : /mnt/scrap/repronim/data/ds000003-qc/sourcedata/sub-13/anat/sub-13_T1w.nii.gz
* metadata : {}
* modality : T1w
* out_dir : /mnt/scrap/repronim/data/ds000003-qc
* provenance : {'md5sum': '70943c0c983c78262efbe9c2cdbf6046', 'settings': {'testing': False}, 'software': 'mriqc', 'version': '0.15.1', 'warnings': {'large_rot_frame': True, 'small_air_mask': False}, 'webapi_port': None, 'webapi_url': 'https://mriqc.nimh.nih.gov/api/v1'}
* rec_id : <undefined>
* root : {'cjv': 0.30096555729834085, 'cnr': 4.301534086768522, 'efc': 0.49646090043466895, 'fber': 425.31781005859375, 'fwhm_avg': 3.685813264693222, 'fwhm_x': 4.1479, 'fwhm_y': 3.41321989827812, 'fwhm_z': 3.4963198958015473, 'icvs_csf': 0.23647801236256863, 'icvs_gm': 0.40808804429148315, 'icvs_wm': 0.35543394334594824, 'inu_med': 1.6187403202056885, 'inu_range': 0.35118777751922603, 'qi_1': 0.0, 'rpve_csf': 23.925381196749086, 'rpve_gm': 13.845017799530112, 'rpve_wm': 20.140254711860216, 'size_x': 160, 'size_y': 192, 'size_z': 192, 'snr_csf': 1.66962104490042, 'snr_gm': 10.01154543014906, 'snr_total': 11.823895159562355, 'snr_wm': 23.790519003637588, 'snrd_csf': 14.332798628030911, 'snrd_gm': 27.185890453332657, 'snrd_total': 27.60919065402138, 'snrd_wm': 41.30888288070057, 'spacing_x': 1.0, 'spacing_y': 1.3333333730697632, 'spacing_z': 1.3333333730697632, 'summary_bg_k': 4.3869550593336335, 'summary_bg_mad': 15.859513282775879, 'summary_bg_mean': 26.28672218322754, 'summary_bg_median': 24.26691436767578, 'summary_bg_n': 2275392.0, 'summary_bg_p05': 5.393754482269287, 'summary_bg_p95': 53.798627471923815, 'summary_bg_stdv': 15.154520988464355, 'summary_csf_k': 77.47639047176865, 'summary_csf_mad': 81.69718170166016, 'summary_csf_mean': 353.3016357421875, 'summary_csf_median': 346.9677734375, 'summary_csf_n': 7834.0, 'summary_csf_p05': 133.69614639282227, 'summary_csf_p95': 480.63310089111326, 'summary_csf_stdv': 207.7990264892578, 'summary_gm_k': 0.11762648793943198, 'summary_gm_mad': 64.4017562866211, 'summary_gm_mean': 657.9758911132812, 'summary_gm_median': 658.1148681640625, 'summary_gm_n': 9314.0, 'summary_gm_p05': 549.2549224853516, 'summary_gm_p95': 767.0577606201173, 'summary_gm_stdv': 65.73206329345703, 'summary_wm_k': 0.7954492847423285, 'summary_wm_mad': 38.4949951171875, 'summary_wm_mean': 997.9492797851562, 'summary_wm_median': 1000.003662109375, 'summary_wm_n': 89420.0, 'summary_wm_p05': 925.141323852539, 'summary_wm_p95': 1062.7960632324218, 'summary_wm_stdv': 42.033470153808594, 'tpm_overlap_csf': 0.22582228481769562, 'tpm_overlap_gm': 0.5293856859207153, 'tpm_overlap_wm': 0.6000604033470154, 'wm2max': 0.5883010263274695}
* run_id : <undefined>
* session_id : <undefined>
* subject_id : 13
* task_id : <undefined>

Execution Inputs
----------------


* _outputs : {'qi_2': 0.005237149922495059}
* acq_id : <undefined>
* dataset : unknown
* in_file : /mnt/scrap/repronim/data/ds000003-qc/sourcedata/sub-13/anat/sub-13_T1w.nii.gz
* metadata : {}
* modality : T1w
* out_dir : /mnt/scrap/repronim/data/ds000003-qc
* provenance : {'md5sum': '70943c0c983c78262efbe9c2cdbf6046', 'settings': {'testing': False}, 'software': 'mriqc', 'version': '0.15.1', 'warnings': {'large_rot_frame': True, 'small_air_mask': False}, 'webapi_port': None, 'webapi_url': 'https://mriqc.nimh.nih.gov/api/v1'}
* rec_id : <undefined>
* root : {'cjv': 0.30096555729834085, 'cnr': 4.301534086768522, 'efc': 0.49646090043466895, 'fber': 425.31781005859375, 'fwhm_avg': 3.685813264693222, 'fwhm_x': 4.1479, 'fwhm_y': 3.41321989827812, 'fwhm_z': 3.4963198958015473, 'icvs_csf': 0.23647801236256863, 'icvs_gm': 0.40808804429148315, 'icvs_wm': 0.35543394334594824, 'inu_med': 1.6187403202056885, 'inu_range': 0.35118777751922603, 'qi_1': 0.0, 'rpve_csf': 23.925381196749086, 'rpve_gm': 13.845017799530112, 'rpve_wm': 20.140254711860216, 'size_x': 160, 'size_y': 192, 'size_z': 192, 'snr_csf': 1.66962104490042, 'snr_gm': 10.01154543014906, 'snr_total': 11.823895159562355, 'snr_wm': 23.790519003637588, 'snrd_csf': 14.332798628030911, 'snrd_gm': 27.185890453332657, 'snrd_total': 27.60919065402138, 'snrd_wm': 41.30888288070057, 'spacing_x': 1.0, 'spacing_y': 1.3333333730697632, 'spacing_z': 1.3333333730697632, 'summary_bg_k': 4.3869550593336335, 'summary_bg_mad': 15.859513282775879, 'summary_bg_mean': 26.28672218322754, 'summary_bg_median': 24.26691436767578, 'summary_bg_n': 2275392.0, 'summary_bg_p05': 5.393754482269287, 'summary_bg_p95': 53.798627471923815, 'summary_bg_stdv': 15.154520988464355, 'summary_csf_k': 77.47639047176865, 'summary_csf_mad': 81.69718170166016, 'summary_csf_mean': 353.3016357421875, 'summary_csf_median': 346.9677734375, 'summary_csf_n': 7834.0, 'summary_csf_p05': 133.69614639282227, 'summary_csf_p95': 480.63310089111326, 'summary_csf_stdv': 207.7990264892578, 'summary_gm_k': 0.11762648793943198, 'summary_gm_mad': 64.4017562866211, 'summary_gm_mean': 657.9758911132812, 'summary_gm_median': 658.1148681640625, 'summary_gm_n': 9314.0, 'summary_gm_p05': 549.2549224853516, 'summary_gm_p95': 767.0577606201173, 'summary_gm_stdv': 65.73206329345703, 'summary_wm_k': 0.7954492847423285, 'summary_wm_mad': 38.4949951171875, 'summary_wm_mean': 997.9492797851562, 'summary_wm_median': 1000.003662109375, 'summary_wm_n': 89420.0, 'summary_wm_p05': 925.141323852539, 'summary_wm_p95': 1062.7960632324218, 'summary_wm_stdv': 42.033470153808594, 'tpm_overlap_csf': 0.22582228481769562, 'tpm_overlap_gm': 0.5293856859207153, 'tpm_overlap_wm': 0.6000604033470154, 'wm2max': 0.5883010263274695, 'qi_2': 0.005237149922495059, 'bids_meta': {'subject_id': '13', 'modality': 'T1w', 'dataset': 'unknown'}, 'provenance': {'md5sum': '70943c0c983c78262efbe9c2cdbf6046', 'settings': {'testing': False}, 'software': 'mriqc', 'version': '0.15.1', 'warnings': {'large_rot_frame': True, 'small_air_mask': False}, 'webapi_port': None, 'webapi_url': 'https://mriqc.nimh.nih.gov/api/v1'}}
* run_id : <undefined>
* session_id : <undefined>
* subject_id : 13
* task_id : <undefined>


Execution Outputs
-----------------


* out_file : /mnt/scrap/repronim/data/ds000003-qc/sub-13/anat/sub-13_T1w.json


Runtime info
------------


* duration : 0.002099
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/datasink


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

