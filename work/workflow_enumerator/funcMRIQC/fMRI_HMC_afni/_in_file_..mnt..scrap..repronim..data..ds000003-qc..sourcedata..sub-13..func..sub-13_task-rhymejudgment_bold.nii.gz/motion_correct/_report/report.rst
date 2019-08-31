Node: funcMRIQC (fMRI_HMC_afni (motion_correct (afni)
=====================================================


 Hierarchy : workflow_enumerator.funcMRIQC.fMRI_HMC_afni.motion_correct
 Exec ID : motion_correct.a1


Original Inputs
---------------


* args : -Fourier -twopass
* basefile : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/gen_ref/ref_bold.nii.gz
* copyorigin : <undefined>
* environ : {}
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/sanitize/sub-13_task-rhymejudgment_bold_valid.nii.gz
* in_weight_volume : <undefined>
* interp : <undefined>
* md1d_file : <undefined>
* num_threads : 1
* oned_file : <undefined>
* oned_matrix_save : <undefined>
* out_file : <undefined>
* outputtype : NIFTI_GZ
* timeshift : <undefined>
* verbose : <undefined>
* zpad : 4

Execution Inputs
----------------


* args : -Fourier -twopass
* basefile : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/gen_ref/ref_bold.nii.gz
* copyorigin : <undefined>
* environ : {}
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/motion_correct/sub-13_task-rhymejudgment_bold_valid.nii.gz
* in_weight_volume : <undefined>
* interp : <undefined>
* md1d_file : <undefined>
* num_threads : 1
* oned_file : <undefined>
* oned_matrix_save : <undefined>
* out_file : <undefined>
* outputtype : NIFTI_GZ
* timeshift : <undefined>
* verbose : <undefined>
* zpad : 4


Execution Outputs
-----------------


* md1d_file : <undefined>
* oned_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/motion_correct/sub-13_task-rhymejudgment_bold_valid.1D
* oned_matrix_save : <undefined>
* out_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/motion_correct/sub-13_task-rhymejudgment_bold_valid_volreg.nii.gz


Runtime info
------------


* command : 3dvolreg -Fourier -twopass -1Dfile sub-13_task-rhymejudgment_bold_valid.1D -1Dmatrix_save sub-13_task-rhymejudgment_bold_valid.aff12.1D -prefix sub-13_task-rhymejudgment_bold_valid_volreg.nii.gz -base /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/gen_ref/ref_bold.nii.gz -zpad 4 -maxdisp1D sub-13_task-rhymejudgment_bold_valid_md.1D /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/motion_correct/sub-13_task-rhymejudgment_bold_valid.nii.gz
* duration : 147.007895
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/motion_correct


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
 v
 o
 l
 r
 e
 g
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
  
 R
 W
  
 C
 o
 x
 

 *
 *
  
 A
 F
 N
 I
  
 c
 o
 n
 v
 e
 r
 t
 s
  
 N
 I
 F
 T
 I
 _
 d
 a
 t
 a
 t
 y
 p
 e
 =
 4
  
 (
 I
 N
 T
 1
 6
 )
  
 i
 n
  
 f
 i
 l
 e
  
 /
 m
 n
 t
 /
 s
 c
 r
 a
 p
 /
 r
 e
 p
 r
 o
 n
 i
 m
 /
 d
 a
 t
 a
 /
 d
 s
 0
 0
 0
 0
 0
 3
 -
 q
 c
 /
 w
 o
 r
 k
 /
 w
 o
 r
 k
 f
 l
 o
 w
 _
 e
 n
 u
 m
 e
 r
 a
 t
 o
 r
 /
 f
 u
 n
 c
 M
 R
 I
 Q
 C
 /
 f
 M
 R
 I
 _
 H
 M
 C
 _
 a
 f
 n
 i
 /
 _
 i
 n
 _
 f
 i
 l
 e
 _
 .
 .
 m
 n
 t
 .
 .
 s
 c
 r
 a
 p
 .
 .
 r
 e
 p
 r
 o
 n
 i
 m
 .
 .
 d
 a
 t
 a
 .
 .
 d
 s
 0
 0
 0
 0
 0
 3
 -
 q
 c
 .
 .
 s
 o
 u
 r
 c
 e
 d
 a
 t
 a
 .
 .
 s
 u
 b
 -
 1
 3
 .
 .
 f
 u
 n
 c
 .
 .
 s
 u
 b
 -
 1
 3
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
 .
 n
 i
 i
 .
 g
 z
 /
 g
 e
 n
 _
 r
 e
 f
 /
 r
 e
 f
 _
 b
 o
 l
 d
 .
 n
 i
 i
 .
 g
 z
  
 t
 o
  
 F
 L
 O
 A
 T
 3
 2
 

  
  
  
  
  
 W
 a
 r
 n
 i
 n
 g
 s
  
 o
 f
  
 t
 h
 i
 s
  
 t
 y
 p
 e
  
 w
 i
 l
 l
  
 b
 e
  
 m
 u
 t
 e
 d
  
 f
 o
 r
  
 t
 h
 i
 s
  
 s
 e
 s
 s
 i
 o
 n
 .
 

  
  
  
  
  
 S
 e
 t
  
 A
 F
 N
 I
 _
 N
 I
 F
 T
 I
 _
 T
 Y
 P
 E
 _
 W
 A
 R
 N
  
 t
 o
  
 Y
 E
 S
  
 t
 o
  
 s
 e
 e
  
 t
 h
 e
 m
  
 a
 l
 l
 ,
  
 N
 O
  
 t
 o
  
 s
 e
 e
  
 n
 o
 n
 e
 .
 

 +
 +
  
 C
 o
 a
 r
 s
 e
  
 d
 e
 l
  
 w
 a
 s
  
 1
 0
 ,
  
 r
 e
 p
 l
 a
 c
 e
 d
  
 w
 i
 t
 h
  
 3
 

 +
 +
  
 M
 a
 x
  
 d
 i
 s
 p
 l
 a
 c
 e
 m
 e
 n
 t
  
 i
 n
  
 a
 u
 t
 o
 m
 a
 s
 k
  
 =
  
 3
 .
 0
 1
  
 (
 m
 m
 )
  
 a
 t
  
 s
 u
 b
 -
 b
 r
 i
 c
 k
  
 1
 5
 7
 

 +
 +
  
 M
 a
 x
  
 d
 e
 l
 t
 a
  
 d
 i
 s
 p
 l
  
  
 i
 n
  
 a
 u
 t
 o
 m
 a
 s
 k
  
 =
  
 0
 .
 4
 2
  
 (
 m
 m
 )
  
 a
 t
  
 s
 u
 b
 -
 b
 r
 i
 c
 k
  
 6
 5


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

