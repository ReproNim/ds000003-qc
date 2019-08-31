Node: funcMRIQC (mean (afni)
============================


 Hierarchy : workflow_enumerator.funcMRIQC.mean
 Exec ID : mean.a0


Original Inputs
---------------


* args : <undefined>
* environ : {}
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/motion_correct/sub-02_task-rhymejudgment_bold_valid_volreg.nii.gz
* mask : <undefined>
* num_threads : 1
* options : -mean
* out_file : <undefined>
* outputtype : NIFTI_GZ

Execution Inputs
----------------


* args : <undefined>
* environ : {}
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/mean/sub-02_task-rhymejudgment_bold_valid_volreg.nii.gz
* mask : <undefined>
* num_threads : 1
* options : -mean
* out_file : <undefined>
* outputtype : NIFTI_GZ


Execution Outputs
-----------------


* out_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/mean/sub-02_task-rhymejudgment_bold_valid_volreg_tstat.nii.gz


Runtime info
------------


* command : 3dTstat -mean -prefix sub-02_task-rhymejudgment_bold_valid_volreg_tstat.nii.gz /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/mean/sub-02_task-rhymejudgment_bold_valid_volreg.nii.gz
* duration : 0.977222
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/mean


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
 T
 s
 t
 a
 t
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
  
 K
 R
  
 H
 a
 m
 m
 e
 t
 t
  
 &
  
 R
 W
  
 C
 o
 x
 

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
 t
 a
 s
 k
 -
 r
 h
 y
 m
 e
 j
 u
 d
 g
 m
 e
 n
 t
 _
 b
 o
 l
 d
 _
 v
 a
 l
 i
 d
 _
 v
 o
 l
 r
 e
 g
 _
 t
 s
 t
 a
 t
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

