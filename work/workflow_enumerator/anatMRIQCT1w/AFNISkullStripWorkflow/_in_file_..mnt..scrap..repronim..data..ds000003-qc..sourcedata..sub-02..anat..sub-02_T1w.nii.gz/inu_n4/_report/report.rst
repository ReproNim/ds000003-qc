Node: anatMRIQCT1w (AFNISkullStripWorkflow (inu_n4 (ants)
=========================================================


 Hierarchy : workflow_enumerator.anatMRIQCT1w.AFNISkullStripWorkflow.inu_n4
 Exec ID : inu_n4.a0


Original Inputs
---------------


* args : <undefined>
* bias_image : <undefined>
* bspline_fitting_distance : <undefined>
* bspline_order : <undefined>
* convergence_threshold : <undefined>
* copy_header : True
* dimension : 3
* environ : {'NSLOTS': '1'}
* input_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/conform/sub-02_T1w_conformed.nii.gz
* mask_image : <undefined>
* n_iterations : <undefined>
* num_threads : 1
* output_image : <undefined>
* save_bias : True
* shrink_factor : <undefined>
* weight_image : <undefined>

Execution Inputs
----------------


* args : <undefined>
* bias_image : <undefined>
* bspline_fitting_distance : <undefined>
* bspline_order : <undefined>
* convergence_threshold : <undefined>
* copy_header : True
* dimension : 3
* environ : {'NSLOTS': '1'}
* input_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/conform/sub-02_T1w_conformed.nii.gz
* mask_image : <undefined>
* n_iterations : <undefined>
* num_threads : 1
* output_image : <undefined>
* save_bias : True
* shrink_factor : <undefined>
* weight_image : <undefined>


Execution Outputs
-----------------


* bias_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/inu_n4/sub-02_T1w_conformed_bias.nii.gz
* output_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/inu_n4/sub-02_T1w_conformed_corrected.nii.gz


Runtime info
------------


* command : N4BiasFieldCorrection -d 3 --input-image /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/conform/sub-02_T1w_conformed.nii.gz --output [ sub-02_T1w_conformed_corrected.nii.gz, sub-02_T1w_conformed_bias.nii.gz ]
* duration : 119.17521
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/inu_n4


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

