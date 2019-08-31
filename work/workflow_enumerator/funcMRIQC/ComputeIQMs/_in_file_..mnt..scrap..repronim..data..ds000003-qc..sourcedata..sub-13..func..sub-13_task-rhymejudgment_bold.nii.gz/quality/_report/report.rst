Node: funcMRIQC (ComputeIQMs (quality (afni)
============================================


 Hierarchy : workflow_enumerator.funcMRIQC.ComputeIQMs.quality
 Exec ID : quality.a1


Original Inputs
---------------


* args : <undefined>
* autoclip : False
* automask : True
* clip : <undefined>
* environ : {}
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/motion_correct/sub-13_task-rhymejudgment_bold_valid_volreg.nii.gz
* interval : False
* mask : <undefined>
* out_file : <undefined>
* quadrant : False
* spearman : False

Execution Inputs
----------------


* args : <undefined>
* autoclip : False
* automask : True
* clip : <undefined>
* environ : {}
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/motion_correct/sub-13_task-rhymejudgment_bold_valid_volreg.nii.gz
* interval : False
* mask : <undefined>
* out_file : <undefined>
* quadrant : False
* spearman : False


Execution Outputs
-----------------


* out_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/quality/sub-13_task-rhymejudgment_bold_valid_volreg_tqual


Runtime info
------------


* command : 3dTqual -automask /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/motion_correct/sub-13_task-rhymejudgment_bold_valid_volreg.nii.gz > sub-13_task-rhymejudgment_bold_valid_volreg_tqual
* duration : 1.350179
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/quality


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
 q
 u
 a
 l
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
 o
 c
 l
 i
 p
  
 v
 a
 l
 u
 e
  
 =
  
 3
 2
 4
 .
 5
 3
 

 +
 +
  
 2
 8
 7
 9
 7
  
 o
 u
 t
  
 o
 f
  
 1
 3
 5
 1
 6
 8
  
 v
 o
 x
 e
 l
 s
  
 s
 u
 r
 v
 i
 v
 e
  
 t
 h
 e
  
 c
 l
 i
 p
 

 +
 +
  
 M
 e
 d
 i
 a
 n
 =
 0
 .
 0
 1
 1
 4
 3
 3
 2
  
  
 M
 e
 d
 i
 a
 n
 -
 3
 .
 5
 *
 M
 A
 D
 =
 0
  
  
 M
 e
 d
 i
 a
 n
 +
 3
 .
 5
 *
 M
 A
 D
 =
 0
 .
 0
 2
 4
 3
 9
 9
 7


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

