Node: anatMRIQCT1w (ComputeIQMs (datasink (bids)
================================================


 Hierarchy : workflow_enumerator.anatMRIQCT1w.ComputeIQMs.datasink
 Exec ID : datasink.a0


Original Inputs
---------------


* _outputs : {'qi_2': 0.00438578455506081}
* acq_id : <undefined>
* dataset : unknown
* in_file : /mnt/scrap/repronim/data/ds000003-qc/sourcedata/sub-02/anat/sub-02_T1w.nii.gz
* metadata : {}
* modality : T1w
* out_dir : /mnt/scrap/repronim/data/ds000003-qc
* provenance : {'md5sum': '89189d319055e674f76f1524706bac81', 'settings': {'testing': False}, 'software': 'mriqc', 'version': '0.15.1', 'warnings': {'large_rot_frame': True, 'small_air_mask': False}, 'webapi_port': None, 'webapi_url': 'https://mriqc.nimh.nih.gov/api/v1'}
* rec_id : <undefined>
* root : {'cjv': 0.3545852255575525, 'cnr': 3.6452762411506203, 'efc': 0.6191508759161556, 'fber': 152.1634979248047, 'fwhm_avg': 3.907529926673772, 'fwhm_x': 4.34133, 'fwhm_y': 3.6982798897826705, 'fwhm_z': 3.682979890238646, 'icvs_csf': 0.2219768320100525, 'icvs_gm': 0.4330981361239126, 'icvs_wm': 0.34492503186603485, 'inu_med': 1.517476201057434, 'inu_range': 0.6488350033760069, 'qi_1': 0.0, 'rpve_csf': 19.247033389620327, 'rpve_gm': 10.217849894639043, 'rpve_wm': 15.271970215366615, 'size_x': 160, 'size_y': 192, 'size_z': 192, 'snr_csf': 1.5178061382602253, 'snr_gm': 8.82545062699851, 'snr_total': 9.439151989927447, 'snr_wm': 17.974199204523604, 'snrd_csf': 9.756678094480645, 'snrd_gm': 15.737553897077843, 'snrd_total': 16.560901356246053, 'snrd_wm': 24.18847207717967, 'spacing_x': 1.0, 'spacing_y': 1.3333333730697632, 'spacing_z': 1.3333333730697632, 'summary_bg_k': 0.5883652130535681, 'summary_bg_mad': 27.085107803344727, 'summary_bg_mean': 46.62661361694336, 'summary_bg_median': 44.14168167114258, 'summary_bg_n': 1535883.0, 'summary_bg_p05': 11.034754085540772, 'summary_bg_p95': 92.51226272583007, 'summary_bg_stdv': 25.61980628967285, 'summary_csf_k': 33.5012549137425, 'summary_csf_mad': 121.92987060546875, 'summary_csf_mean': 408.7982177734375, 'summary_csf_median': 403.367431640625, 'summary_csf_n': 14109.0, 'summary_csf_p05': 123.25566558837892, 'summary_csf_p95': 569.1635253906247, 'summary_csf_stdv': 265.7474670410156, 'summary_gm_k': 0.20750125000952968, 'summary_gm_mad': 71.79725646972656, 'summary_gm_mean': 654.476806640625, 'summary_gm_median': 650.6329956054688, 'summary_gm_n': 16031.0, 'summary_gm_p05': 540.4121398925781, 'summary_gm_p95': 782.6559143066406, 'summary_gm_stdv': 73.72005462646484, 'summary_wm_k': 0.4671401010332654, 'summary_wm_mad': 52.089073181152344, 'summary_wm_mean': 998.4737548828125, 'summary_wm_median': 1000.0167846679688, 'summary_wm_n': 113255.0, 'summary_wm_p05': 903.1322204589844, 'summary_wm_p95': 1086.99267578125, 'summary_wm_stdv': 55.635990142822266, 'tpm_overlap_csf': 0.20529000461101532, 'tpm_overlap_gm': 0.5129110217094421, 'tpm_overlap_wm': 0.5543895363807678, 'wm2max': 0.4429809678719822}
* run_id : <undefined>
* session_id : <undefined>
* subject_id : 02
* task_id : <undefined>

Execution Inputs
----------------


* _outputs : {'qi_2': 0.00438578455506081}
* acq_id : <undefined>
* dataset : unknown
* in_file : /mnt/scrap/repronim/data/ds000003-qc/sourcedata/sub-02/anat/sub-02_T1w.nii.gz
* metadata : {}
* modality : T1w
* out_dir : /mnt/scrap/repronim/data/ds000003-qc
* provenance : {'md5sum': '89189d319055e674f76f1524706bac81', 'settings': {'testing': False}, 'software': 'mriqc', 'version': '0.15.1', 'warnings': {'large_rot_frame': True, 'small_air_mask': False}, 'webapi_port': None, 'webapi_url': 'https://mriqc.nimh.nih.gov/api/v1'}
* rec_id : <undefined>
* root : {'cjv': 0.3545852255575525, 'cnr': 3.6452762411506203, 'efc': 0.6191508759161556, 'fber': 152.1634979248047, 'fwhm_avg': 3.907529926673772, 'fwhm_x': 4.34133, 'fwhm_y': 3.6982798897826705, 'fwhm_z': 3.682979890238646, 'icvs_csf': 0.2219768320100525, 'icvs_gm': 0.4330981361239126, 'icvs_wm': 0.34492503186603485, 'inu_med': 1.517476201057434, 'inu_range': 0.6488350033760069, 'qi_1': 0.0, 'rpve_csf': 19.247033389620327, 'rpve_gm': 10.217849894639043, 'rpve_wm': 15.271970215366615, 'size_x': 160, 'size_y': 192, 'size_z': 192, 'snr_csf': 1.5178061382602253, 'snr_gm': 8.82545062699851, 'snr_total': 9.439151989927447, 'snr_wm': 17.974199204523604, 'snrd_csf': 9.756678094480645, 'snrd_gm': 15.737553897077843, 'snrd_total': 16.560901356246053, 'snrd_wm': 24.18847207717967, 'spacing_x': 1.0, 'spacing_y': 1.3333333730697632, 'spacing_z': 1.3333333730697632, 'summary_bg_k': 0.5883652130535681, 'summary_bg_mad': 27.085107803344727, 'summary_bg_mean': 46.62661361694336, 'summary_bg_median': 44.14168167114258, 'summary_bg_n': 1535883.0, 'summary_bg_p05': 11.034754085540772, 'summary_bg_p95': 92.51226272583007, 'summary_bg_stdv': 25.61980628967285, 'summary_csf_k': 33.5012549137425, 'summary_csf_mad': 121.92987060546875, 'summary_csf_mean': 408.7982177734375, 'summary_csf_median': 403.367431640625, 'summary_csf_n': 14109.0, 'summary_csf_p05': 123.25566558837892, 'summary_csf_p95': 569.1635253906247, 'summary_csf_stdv': 265.7474670410156, 'summary_gm_k': 0.20750125000952968, 'summary_gm_mad': 71.79725646972656, 'summary_gm_mean': 654.476806640625, 'summary_gm_median': 650.6329956054688, 'summary_gm_n': 16031.0, 'summary_gm_p05': 540.4121398925781, 'summary_gm_p95': 782.6559143066406, 'summary_gm_stdv': 73.72005462646484, 'summary_wm_k': 0.4671401010332654, 'summary_wm_mad': 52.089073181152344, 'summary_wm_mean': 998.4737548828125, 'summary_wm_median': 1000.0167846679688, 'summary_wm_n': 113255.0, 'summary_wm_p05': 903.1322204589844, 'summary_wm_p95': 1086.99267578125, 'summary_wm_stdv': 55.635990142822266, 'tpm_overlap_csf': 0.20529000461101532, 'tpm_overlap_gm': 0.5129110217094421, 'tpm_overlap_wm': 0.5543895363807678, 'wm2max': 0.4429809678719822, 'qi_2': 0.00438578455506081, 'bids_meta': {'subject_id': '02', 'modality': 'T1w', 'dataset': 'unknown'}, 'provenance': {'md5sum': '89189d319055e674f76f1524706bac81', 'settings': {'testing': False}, 'software': 'mriqc', 'version': '0.15.1', 'warnings': {'large_rot_frame': True, 'small_air_mask': False}, 'webapi_port': None, 'webapi_url': 'https://mriqc.nimh.nih.gov/api/v1'}}
* run_id : <undefined>
* session_id : <undefined>
* subject_id : 02
* task_id : <undefined>


Execution Outputs
-----------------


* out_file : /mnt/scrap/repronim/data/ds000003-qc/sub-02/anat/sub-02_T1w.json


Runtime info
------------


* duration : 0.001585
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/datasink


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

