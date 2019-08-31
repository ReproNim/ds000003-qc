Node: funcMRIQC (ComputeIQMs (outliers (afni)
=============================================


 Hierarchy : workflow_enumerator.funcMRIQC.ComputeIQMs.outliers
 Exec ID : outliers.a0


Original Inputs
---------------


* args : <undefined>
* autoclip : False
* automask : False
* environ : {}
* fraction : True
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/motion_correct/sub-02_task-rhymejudgment_bold_valid_volreg.nii.gz
* interval : False
* legendre : False
* mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/erode/sub-02_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz
* out_file : outliers.out
* outliers_file : <undefined>
* polort : <undefined>
* qthr : 0.001
* save_outliers : False

Execution Inputs
----------------


* args : <undefined>
* autoclip : False
* automask : False
* environ : {}
* fraction : True
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/motion_correct/sub-02_task-rhymejudgment_bold_valid_volreg.nii.gz
* interval : False
* legendre : False
* mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/erode/sub-02_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz
* out_file : outliers.out
* outliers_file : <undefined>
* polort : <undefined>
* qthr : 0.001
* save_outliers : False


Execution Outputs
-----------------


* out_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/outliers/outliers.out
* out_outliers : <undefined>


Runtime info
------------


* command : 3dToutcount -fraction -mask /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/erode/sub-02_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz -qthr 0.00100 /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/motion_correct/sub-02_task-rhymejudgment_bold_valid_volreg.nii.gz
* duration : 1.881084
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/outliers


Terminal output
~~~~~~~~~~~~~~~





Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~


 0
 .
 0
 0
 5
 9
 4
 

 0
 .
 0
 0
 6
 0
 5
 

 0
 .
 0
 0
 4
 8
 4
 

 0
 .
 0
 0
 4
 2
 5
 

 0
 .
 0
 0
 4
 8
 7
 

 0
 .
 0
 0
 4
 2
 0
 

 0
 .
 0
 0
 3
 2
 8
 

 0
 .
 0
 0
 4
 3
 0
 

 0
 .
 0
 0
 5
 0
 6
 

 0
 .
 0
 0
 4
 6
 1
 

 0
 .
 0
 0
 3
 8
 5
 

 0
 .
 0
 0
 3
 7
 8
 

 0
 .
 0
 0
 4
 0
 8
 

 0
 .
 0
 0
 4
 0
 6
 

 0
 .
 0
 0
 3
 8
 9
 

 0
 .
 0
 0
 3
 7
 3
 

 0
 .
 0
 0
 3
 5
 9
 

 0
 .
 0
 0
 3
 1
 8
 

 0
 .
 0
 0
 2
 3
 3
 

 0
 .
 0
 0
 1
 9
 2
 

 0
 .
 0
 0
 1
 8
 3
 

 0
 .
 0
 0
 2
 1
 1
 

 0
 .
 0
 0
 1
 1
 9
 

 0
 .
 0
 0
 1
 3
 3
 

 0
 .
 0
 0
 1
 2
 6
 

 0
 .
 0
 0
 1
 1
 9
 

 0
 .
 0
 0
 0
 8
 3
 

 0
 .
 0
 0
 1
 0
 4
 

 0
 .
 0
 0
 1
 0
 4
 

 0
 .
 0
 0
 1
 0
 0
 

 0
 .
 0
 0
 0
 7
 6
 

 0
 .
 0
 0
 0
 5
 0
 

 0
 .
 0
 0
 0
 6
 2
 

 0
 .
 0
 0
 0
 4
 0
 

 0
 .
 0
 0
 0
 6
 4
 

 0
 .
 0
 0
 0
 6
 9
 

 0
 .
 0
 0
 0
 4
 0
 

 0
 .
 0
 0
 0
 4
 5
 

 0
 .
 0
 0
 0
 4
 0
 

 0
 .
 0
 0
 0
 3
 8
 

 0
 .
 0
 0
 0
 4
 3
 

 0
 .
 0
 0
 0
 5
 7
 

 0
 .
 0
 0
 0
 3
 3
 

 0
 .
 0
 0
 0
 2
 6
 

 0
 .
 0
 0
 0
 3
 1
 

 0
 .
 0
 0
 0
 3
 6
 

 0
 .
 0
 0
 0
 3
 8
 

 0
 .
 0
 0
 0
 4
 7
 

 0
 .
 0
 0
 0
 4
 0
 

 0
 .
 0
 0
 0
 5
 7
 

 0
 .
 0
 0
 0
 4
 0
 

 0
 .
 0
 0
 0
 5
 0
 

 0
 .
 0
 0
 0
 4
 5
 

 0
 .
 0
 0
 0
 4
 3
 

 0
 .
 0
 0
 0
 3
 6
 

 0
 .
 0
 0
 0
 4
 5
 

 0
 .
 0
 0
 0
 3
 1
 

 0
 .
 0
 0
 0
 1
 9
 

 0
 .
 0
 0
 0
 2
 1
 

 0
 .
 0
 0
 0
 5
 5
 

 0
 .
 0
 0
 0
 3
 8
 

 0
 .
 0
 0
 0
 5
 5
 

 0
 .
 0
 0
 0
 3
 8
 

 0
 .
 0
 0
 0
 2
 4
 

 0
 .
 0
 0
 0
 3
 8
 

 0
 .
 0
 0
 0
 0
 9
 

 0
 .
 0
 0
 0
 1
 7
 

 0
 .
 0
 0
 0
 2
 4
 

 0
 .
 0
 0
 0
 2
 6
 

 0
 .
 0
 0
 0
 2
 6
 

 0
 .
 0
 0
 0
 3
 1
 

 0
 .
 0
 0
 0
 2
 4
 

 0
 .
 0
 0
 0
 0
 9
 

 0
 .
 0
 0
 0
 1
 2
 

 0
 .
 0
 0
 0
 2
 1
 

 0
 .
 0
 0
 0
 0
 9
 

 0
 .
 0
 0
 0
 2
 6
 

 0
 .
 0
 0
 0
 1
 7
 

 0
 .
 0
 0
 0
 1
 7
 

 0
 .
 0
 0
 0
 1
 9
 

 0
 .
 0
 0
 0
 0
 9
 

 0
 .
 0
 0
 0
 0
 9
 

 0
 .
 0
 0
 0
 1
 4
 

 0
 .
 0
 0
 0
 3
 1
 

 0
 .
 0
 0
 0
 3
 1
 

 0
 .
 0
 0
 0
 4
 5
 

 0
 .
 0
 0
 0
 4
 7
 

 0
 .
 0
 0
 0
 3
 6
 

 0
 .
 0
 0
 0
 1
 9
 

 0
 .
 0
 0
 0
 2
 8
 

 0
 .
 0
 0
 0
 3
 6
 

 0
 .
 0
 0
 0
 1
 9
 

 0
 .
 0
 0
 0
 2
 8
 

 0
 .
 0
 0
 0
 2
 4
 

 0
 .
 0
 0
 0
 1
 2
 

 0
 .
 0
 0
 0
 1
 9
 

 0
 .
 0
 0
 0
 3
 6
 

 0
 .
 0
 0
 0
 0
 9
 

 0
 .
 0
 0
 0
 3
 3
 

 0
 .
 0
 0
 0
 2
 1
 

 0
 .
 0
 0
 0
 6
 2
 

 0
 .
 0
 0
 0
 3
 3
 

 0
 .
 0
 0
 0
 2
 4
 

 0
 .
 0
 0
 0
 2
 6
 

 0
 .
 0
 0
 0
 0
 9
 

 0
 .
 0
 0
 0
 1
 7
 

 0
 .
 0
 0
 0
 0
 7
 

 0
 .
 0
 0
 0
 3
 3
 

 0
 .
 0
 0
 0
 1
 9
 

 0
 .
 0
 0
 0
 1
 4
 

 0
 .
 0
 0
 0
 2
 8
 

 0
 .
 0
 0
 0
 2
 8
 

 0
 .
 0
 0
 0
 1
 4
 

 0
 .
 0
 0
 0
 2
 6
 

 0
 .
 0
 0
 0
 2
 6
 

 0
 .
 0
 0
 0
 9
 7
 

 0
 .
 0
 0
 0
 5
 9
 

 0
 .
 0
 0
 1
 0
 2
 

 0
 .
 0
 0
 1
 4
 7
 

 0
 .
 0
 0
 2
 9
 7
 

 0
 .
 0
 0
 1
 1
 6
 

 0
 .
 0
 0
 0
 6
 2
 

 0
 .
 0
 0
 1
 2
 6
 

 0
 .
 0
 0
 0
 9
 7
 

 0
 .
 0
 0
 1
 6
 6
 

 0
 .
 0
 0
 1
 5
 4
 

 0
 .
 0
 0
 2
 0
 4
 

 0
 .
 0
 0
 1
 6
 1
 

 0
 .
 0
 0
 1
 3
 3
 

 0
 .
 0
 0
 1
 3
 5
 

 0
 .
 0
 0
 1
 5
 4
 

 0
 .
 0
 0
 0
 9
 3
 

 0
 .
 0
 0
 0
 7
 1
 

 0
 .
 0
 0
 0
 7
 6
 

 0
 .
 0
 0
 0
 6
 6
 

 0
 .
 0
 0
 0
 8
 1
 

 0
 .
 0
 0
 1
 4
 7
 

 0
 .
 0
 0
 0
 5
 9
 

 0
 .
 0
 0
 0
 7
 4
 

 0
 .
 0
 0
 0
 7
 8
 

 0
 .
 0
 0
 0
 9
 5
 

 0
 .
 0
 0
 1
 4
 5
 

 0
 .
 0
 0
 0
 8
 3
 

 0
 .
 0
 0
 0
 8
 3
 

 0
 .
 0
 0
 0
 8
 8
 

 0
 .
 0
 0
 0
 7
 4
 

 0
 .
 0
 0
 0
 5
 2
 

 0
 .
 0
 0
 0
 3
 8
 

 0
 .
 0
 0
 0
 6
 2
 

 0
 .
 0
 0
 0
 7
 8
 

 0
 .
 0
 0
 0
 7
 1
 

 0
 .
 0
 0
 0
 8
 8
 

 0
 .
 0
 0
 0
 8
 3
 

 0
 .
 0
 0
 0
 9
 5
 

 0
 .
 0
 0
 0
 8
 5
 

 0
 .
 0
 0
 0
 8
 8
 

 0
 .
 0
 0
 1
 1
 4
 

 0
 .
 0
 0
 0
 5
 2
 

 0
 .
 0
 0
 0
 5
 9


Terminal - standard error
~~~~~~~~~~~~~~~~~~~~~~~~~


 +
 +
  
 3
 d
 T
 o
 u
 t
 c
 o
 u
 n
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
  
 4
 2
 1
 1
 8
  
 v
 o
 x
 e
 l
 s
  
 i
 n
  
 t
 h
 e
  
 m
 a
 s
 k
 

 +
 +
  
 4
 2
 1
 1
 8
  
 v
 o
 x
 e
 l
 s
  
 p
 a
 s
 s
 e
 d
  
 m
 a
 s
 k
 /
 c
 l
 i
 p


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

