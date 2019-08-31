Node: anatMRIQCT1w (AFNISkullStripWorkflow (binarize (fsl)
==========================================================


 Hierarchy : workflow_enumerator.anatMRIQCT1w.AFNISkullStripWorkflow.binarize
 Exec ID : binarize.a0


Original Inputs
---------------


* args : -bin
* direction : below
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/sstrip_orig_vol/sub-02_T1w_conformed_calc.nii.gz
* internal_datatype : <undefined>
* nan2zeros : <undefined>
* out_file : <undefined>
* output_datatype : <undefined>
* output_type : NIFTI_GZ
* thresh : 0.001
* use_nonzero_voxels : <undefined>
* use_robust_range : <undefined>

Execution Inputs
----------------


* args : -bin
* direction : below
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/sstrip_orig_vol/sub-02_T1w_conformed_calc.nii.gz
* internal_datatype : <undefined>
* nan2zeros : <undefined>
* out_file : <undefined>
* output_datatype : <undefined>
* output_type : NIFTI_GZ
* thresh : 0.001
* use_nonzero_voxels : <undefined>
* use_robust_range : <undefined>


Execution Outputs
-----------------


* out_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/binarize/sub-02_T1w_conformed_calc_thresh.nii.gz


Runtime info
------------


* command : fslmaths /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/sstrip_orig_vol/sub-02_T1w_conformed_calc.nii.gz -thr 0.0010000000 -bin /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/binarize/sub-02_T1w_conformed_calc_thresh.nii.gz
* duration : 0.642011
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/binarize


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

