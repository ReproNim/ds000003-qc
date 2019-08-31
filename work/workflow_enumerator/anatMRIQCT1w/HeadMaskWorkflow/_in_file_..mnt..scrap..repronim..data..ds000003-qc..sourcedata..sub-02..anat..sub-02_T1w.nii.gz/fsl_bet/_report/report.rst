Node: anatMRIQCT1w (HeadMaskWorkflow (fsl_bet (fsl)
===================================================


 Hierarchy : workflow_enumerator.anatMRIQCT1w.HeadMaskWorkflow.fsl_bet
 Exec ID : fsl_bet.a0


Original Inputs
---------------


* args : <undefined>
* center : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* frac : <undefined>
* functional : <undefined>
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/inu_n4/sub-02_T1w_conformed_corrected.nii.gz
* mask : <undefined>
* mesh : <undefined>
* no_output : <undefined>
* out_file : <undefined>
* outline : <undefined>
* output_type : NIFTI_GZ
* padding : <undefined>
* radius : <undefined>
* reduce_bias : <undefined>
* remove_eyes : <undefined>
* robust : <undefined>
* skull : <undefined>
* surfaces : True
* t2_guided : <undefined>
* threshold : <undefined>
* vertical_gradient : <undefined>

Execution Inputs
----------------


* args : <undefined>
* center : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* frac : <undefined>
* functional : <undefined>
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/inu_n4/sub-02_T1w_conformed_corrected.nii.gz
* mask : <undefined>
* mesh : <undefined>
* no_output : <undefined>
* out_file : <undefined>
* outline : <undefined>
* output_type : NIFTI_GZ
* padding : <undefined>
* radius : <undefined>
* reduce_bias : <undefined>
* remove_eyes : <undefined>
* robust : <undefined>
* skull : <undefined>
* surfaces : True
* t2_guided : <undefined>
* threshold : <undefined>
* vertical_gradient : <undefined>


Execution Outputs
-----------------


* inskull_mask_file : <undefined>
* inskull_mesh_file : <undefined>
* mask_file : <undefined>
* meshfile : <undefined>
* out_file : <undefined>
* outline_file : <undefined>
* outskin_mask_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/HeadMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/fsl_bet/sub-02_T1w_conformed_corrected_brain_outskin_mask.nii.gz
* outskin_mesh_file : <undefined>
* outskull_mask_file : <undefined>
* outskull_mesh_file : <undefined>
* skull_mask_file : <undefined>


Runtime info
------------


* command : bet /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/inu_n4/sub-02_T1w_conformed_corrected.nii.gz /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/HeadMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/fsl_bet/sub-02_T1w_conformed_corrected_brain.nii.gz -A
* duration : 84.8657
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/HeadMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/fsl_bet


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
* OMP_NUM_THREADS : 1
* PATH : /usr/local/miniconda/bin:/opt/afni:/usr/lib/ants:/usr/lib/fsl/5.0:/usr/lib/afni/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
* POSSUMDIR : /usr/share/fsl/5.0
* PS1 : Singularity> 
* PWD : /mnt/scrap/repronim/data/ds000003-qc
* PYTHONNOUSERSITE : 1
* SINGULARITY_CONTAINER : MD5E-s2914574367--827e2277cfe2e482546b18535ca18251.1.sing
* SINGULARITY_NAME : MD5E-s2914574367--827e2277cfe2e482546b18535ca18251.1.sing
* TERM : screen

