Node: funcMRIQC (SpatialNormalization (EPI2MNI (registration)
=============================================================


 Hierarchy : workflow_enumerator.funcMRIQC.SpatialNormalization.EPI2MNI
 Exec ID : EPI2MNI.a0


Original Inputs
---------------


* compress_report : auto
* explicit_masking : False
* flavor : precise
* float : False
* initial_moving_transform : <undefined>
* lesion_mask : <undefined>
* moving : boldref
* moving_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/SharpenEPI/sub-02_task-rhymejudgment_bold_valid_volreg_tstat_corrected.nii.gz
* moving_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/erode/sub-02_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz
* num_threads : 1
* orientation : RAS
* out_report : report.svg
* reference : boldref
* reference_image : /home/bidsapp/.cache/templateflow/tpl-MNI152NLin2009cAsym/tpl-MNI152NLin2009cAsym_res-02_desc-fMRIPrep_boldref.nii.gz
* reference_mask : /home/bidsapp/.cache/templateflow/tpl-MNI152NLin2009cAsym/tpl-MNI152NLin2009cAsym_res-02_desc-brain_mask.nii.gz
* settings : <undefined>
* template : MNI152NLin2009cAsym
* template_resolution : 2
* template_spec : <undefined>

Execution Inputs
----------------


* compress_report : auto
* explicit_masking : False
* flavor : precise
* float : False
* initial_moving_transform : <undefined>
* lesion_mask : <undefined>
* moving : boldref
* moving_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/SharpenEPI/sub-02_task-rhymejudgment_bold_valid_volreg_tstat_corrected.nii.gz
* moving_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/erode/sub-02_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz
* num_threads : 1
* orientation : RAS
* out_report : report.svg
* reference : boldref
* reference_image : /home/bidsapp/.cache/templateflow/tpl-MNI152NLin2009cAsym/tpl-MNI152NLin2009cAsym_res-02_desc-fMRIPrep_boldref.nii.gz
* reference_mask : /home/bidsapp/.cache/templateflow/tpl-MNI152NLin2009cAsym/tpl-MNI152NLin2009cAsym_res-02_desc-brain_mask.nii.gz
* settings : <undefined>
* template : MNI152NLin2009cAsym
* template_resolution : 2
* template_spec : <undefined>


Execution Outputs
-----------------


* composite_transform : <undefined>
* elapsed_time : <undefined>
* forward_invert_flags : <undefined>
* forward_transforms : <undefined>
* inverse_composite_transform : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/EPI2MNI/epi_to_mniInverseComposite.h5
* inverse_warped_image : <undefined>
* metric_value : <undefined>
* out_report : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/EPI2MNI/report.svg
* reference_image : <undefined>
* reverse_invert_flags : <undefined>
* reverse_transforms : <undefined>
* save_state : <undefined>
* warped_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/EPI2MNI/epi_to_mni_Warped.nii.gz


Runtime info
------------


* duration : 232.058632
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/EPI2MNI


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

