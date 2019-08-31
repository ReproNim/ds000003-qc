Node: anatMRIQCT1w (AirMaskWorkflow (invert_xfm (ants)
======================================================


 Hierarchy : workflow_enumerator.anatMRIQCT1w.AirMaskWorkflow.invert_xfm
 Exec ID : invert_xfm.a0


Original Inputs
---------------


* args : <undefined>
* default_value : 0.0
* dimension : 3
* environ : {'NSLOTS': '1'}
* float : True
* input_image : /home/bidsapp/.cache/templateflow/tpl-MNI152NLin2009cAsym/tpl-MNI152NLin2009cAsym_res-01_desc-head_mask.nii.gz
* input_image_type : <undefined>
* interpolation : MultiLabel
* interpolation_parameters : <undefined>
* invert_transform_flags : <undefined>
* num_threads : 1
* out_postfix : _trans
* output_image : <undefined>
* print_out_composite_warp_file : <undefined>
* reference_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/binarize/sub-02_T1w_conformed_calc_thresh.nii.gz
* transforms : ['/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/SpatialNormalization/ants_t1_to_mniInverseComposite.h5']

Execution Inputs
----------------


* args : <undefined>
* default_value : 0.0
* dimension : 3
* environ : {'NSLOTS': '1'}
* float : True
* input_image : /home/bidsapp/.cache/templateflow/tpl-MNI152NLin2009cAsym/tpl-MNI152NLin2009cAsym_res-01_desc-head_mask.nii.gz
* input_image_type : <undefined>
* interpolation : MultiLabel
* interpolation_parameters : <undefined>
* invert_transform_flags : <undefined>
* num_threads : 1
* out_postfix : _trans
* output_image : <undefined>
* print_out_composite_warp_file : <undefined>
* reference_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/binarize/sub-02_T1w_conformed_calc_thresh.nii.gz
* transforms : ['/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/SpatialNormalization/ants_t1_to_mniInverseComposite.h5']


Execution Outputs
-----------------


* output_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AirMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/invert_xfm/tpl-MNI152NLin2009cAsym_res-01_desc-head_mask_trans.nii.gz


Runtime info
------------


* command : antsApplyTransforms --default-value 0 --dimensionality 3 --float 1 --input /home/bidsapp/.cache/templateflow/tpl-MNI152NLin2009cAsym/tpl-MNI152NLin2009cAsym_res-01_desc-head_mask.nii.gz --interpolation MultiLabel --output tpl-MNI152NLin2009cAsym_res-01_desc-head_mask_trans.nii.gz --reference-image /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/binarize/sub-02_T1w_conformed_calc_thresh.nii.gz --transform /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/SpatialNormalization/ants_t1_to_mniInverseComposite.h5
* duration : 80.178749
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AirMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/invert_xfm


Terminal output
~~~~~~~~~~~~~~~





Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~





Terminal - standard error
~~~~~~~~~~~~~~~~~~~~~~~~~





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
* NSLOTS : 1
* OMP_NUM_THREADS : 1
* PATH : /usr/local/miniconda/bin:/opt/afni:/usr/lib/ants:/usr/lib/fsl/5.0:/usr/lib/afni/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
* POSSUMDIR : /usr/share/fsl/5.0
* PS1 : Singularity> 
* PWD : /mnt/scrap/repronim/data/ds000003-qc
* PYTHONNOUSERSITE : 1
* SINGULARITY_CONTAINER : MD5E-s2914574367--827e2277cfe2e482546b18535ca18251.1.sing
* SINGULARITY_NAME : MD5E-s2914574367--827e2277cfe2e482546b18535ca18251.1.sing
* TERM : screen

