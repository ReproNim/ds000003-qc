Node: anatMRIQCT1w (AFNISkullStripWorkflow (sstrip_orig_vol (afni)
==================================================================


 Hierarchy : workflow_enumerator.anatMRIQCT1w.AFNISkullStripWorkflow.sstrip_orig_vol
 Exec ID : sstrip_orig_vol.a0


Original Inputs
---------------


* args : <undefined>
* environ : {}
* expr : a*step(b)
* in_file_a : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/conform/sub-02_T1w_conformed.nii.gz
* in_file_b : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/skullstrip/sub-02_T1w_conformed_corrected_skullstrip.nii.gz
* in_file_c : <undefined>
* num_threads : 1
* other : <undefined>
* out_file : <undefined>
* outputtype : NIFTI_GZ
* overwrite : <undefined>
* single_idx : <undefined>
* start_idx : <undefined>
* stop_idx : <undefined>

Execution Inputs
----------------


* args : <undefined>
* environ : {}
* expr : a*step(b)
* in_file_a : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/conform/sub-02_T1w_conformed.nii.gz
* in_file_b : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/skullstrip/sub-02_T1w_conformed_corrected_skullstrip.nii.gz
* in_file_c : <undefined>
* num_threads : 1
* other : <undefined>
* out_file : <undefined>
* outputtype : NIFTI_GZ
* overwrite : <undefined>
* single_idx : <undefined>
* start_idx : <undefined>
* stop_idx : <undefined>


Execution Outputs
-----------------


* out_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/sstrip_orig_vol/sub-02_T1w_conformed_calc.nii.gz


Runtime info
------------


* command : 3dcalc -a /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/conform/sub-02_T1w_conformed.nii.gz -b /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/skullstrip/sub-02_T1w_conformed_corrected_skullstrip.nii.gz -expr "a*step(b)" -prefix sub-02_T1w_conformed_calc.nii.gz
* duration : 0.86194
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/sstrip_orig_vol


Terminal output
~~~~~~~~~~~~~~~





Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~





Terminal - standard error
~~~~~~~~~~~~~~~~~~~~~~~~~


 +
 +
  
 3
 d
 c
 a
 l
 c
 :
  
 A
 F
 N
 I
  
 v
 e
 r
 s
 i
 o
 n
 =
 A
 F
 N
 I
 _
 1
 7
 .
 3
 .
 0
 3
  
 (
 N
 o
 v
  
  
 9
  
 2
 0
 1
 7
 )
  
 [
 6
 4
 -
 b
 i
 t
 ]
 

 +
 +
  
 A
 u
 t
 h
 o
 r
 e
 d
  
 b
 y
 :
  
 A
  
 c
 a
 s
 t
  
 o
 f
  
 t
 h
 o
 u
 s
 a
 n
 d
 s
 

 +
 +
  
 O
 u
 t
 p
 u
 t
  
 d
 a
 t
 a
 s
 e
 t
  
 .
 /
 s
 u
 b
 -
 0
 2
 _
 T
 1
 w
 _
 c
 o
 n
 f
 o
 r
 m
 e
 d
 _
 c
 a
 l
 c
 .
 n
 i
 i
 .
 g
 z


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

