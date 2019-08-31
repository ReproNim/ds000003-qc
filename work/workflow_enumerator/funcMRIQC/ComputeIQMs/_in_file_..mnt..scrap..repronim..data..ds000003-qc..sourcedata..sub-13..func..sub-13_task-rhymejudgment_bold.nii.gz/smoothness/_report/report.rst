Node: funcMRIQC (ComputeIQMs (smoothness (afni)
===============================================


 Hierarchy : workflow_enumerator.funcMRIQC.ComputeIQMs.smoothness
 Exec ID : smoothness.a1


Original Inputs
---------------


* acf : False
* args : -ShowMeClassicFWHM
* arith : <undefined>
* automask : False
* combine : True
* compat : <undefined>
* demed : <undefined>
* detrend : True
* environ : {}
* geom : <undefined>
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/mean/sub-13_task-rhymejudgment_bold_valid_volreg_tstat.nii.gz
* mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/erode/sub-13_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz
* out_detrend : <undefined>
* out_file : <undefined>
* out_subbricks : <undefined>
* unif : <undefined>

Execution Inputs
----------------


* acf : False
* args : -ShowMeClassicFWHM
* arith : <undefined>
* automask : False
* combine : True
* compat : <undefined>
* demed : <undefined>
* detrend : True
* environ : {}
* geom : <undefined>
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/mean/sub-13_task-rhymejudgment_bold_valid_volreg_tstat.nii.gz
* mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/erode/sub-13_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz
* out_detrend : <undefined>
* out_file : <undefined>
* out_subbricks : <undefined>
* unif : <undefined>


Execution Outputs
-----------------


* acf_param : <undefined>
* fwhm : (8.1672, 9.91083, 9.28207, 9.09095)
* out_acf : <undefined>
* out_detrend : <undefined>
* out_file : <undefined>
* out_subbricks : <undefined>


Runtime info
------------


* command : 3dFWHMx -ShowMeClassicFWHM -combine -detrend -input /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/mean/sub-13_task-rhymejudgment_bold_valid_volreg_tstat.nii.gz -mask /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/erode/sub-13_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz -detprefix sub-13_task-rhymejudgment_bold_valid_volreg_tstat_detrend -out sub-13_task-rhymejudgment_bold_valid_volreg_tstat_subbricks.out > sub-13_task-rhymejudgment_bold_valid_volreg_tstat_fwhmx.out
* duration : 1.445793
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/smoothness


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
 F
 W
 H
 M
 x
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
  
 T
 h
 e
  
 B
 o
 b
 

 
 [
 7
 m
 *
 +
  
 W
 A
 R
 N
 I
 N
 G
 :
 
 [
 0
 m
  
 U
 s
 i
 n
 g
  
 t
 h
 e
  
 '
 C
 l
 a
 s
 s
 i
 c
 '
  
 G
 a
 u
 s
 s
 i
 a
 n
  
 F
 W
 H
 M
  
 i
 s
  
 n
 o
 t
  
 r
 e
 c
 o
 m
 m
 e
 n
 d
 e
 d
  
 :
 (
 

  
 +
  
  
 T
 h
 e
  
 '
 -
 a
 c
 f
 '
  
 m
 e
 t
 h
 o
 d
  
 g
 i
 v
 e
 s
  
 a
  
 F
 W
 H
 M
  
 e
 s
 t
 i
 m
 a
 t
 e
  
 w
 h
 i
 c
 h
  
 i
 s
  
 m
 o
 r
 e
  
 r
 o
 b
 u
 s
 t
 ;
 

  
 +
  
  
 h
 o
 w
 e
 v
 e
 r
 ,
  
 a
 s
 s
 u
 m
 i
 n
 g
  
 t
 h
 e
  
 s
 p
 a
 t
 i
 a
 l
  
 c
 o
 r
 r
 e
 l
 a
 t
 i
 o
 n
  
 o
 f
  
 F
 M
 R
 I
  
 n
 o
 i
 s
 e
  
 h
 a
 s
 

  
 +
  
  
 a
  
 G
 a
 u
 s
 s
 i
 a
 n
  
 s
 h
 a
 p
 e
  
 i
 s
  
 n
 o
 t
  
 a
  
 g
 o
 o
 d
  
 m
 o
 d
 e
 l
 .
 

 +
 +
  
 N
 u
 m
 b
 e
 r
  
 o
 f
  
 v
 o
 x
 e
 l
 s
  
 i
 n
  
 m
 a
 s
 k
  
 =
  
 3
 4
 6
 7
 4
 

 
 [
 7
 m
 *
 +
  
 W
 A
 R
 N
 I
 N
 G
 :
 
 [
 0
 m
  
 -
 d
 e
 m
 e
 d
  
 a
 n
 d
 /
 o
 r
  
 -
 c
 o
 r
 d
 e
 r
  
 a
 n
 d
 /
 o
 r
  
 -
 u
 n
 i
 f
  
 i
 g
 n
 o
 r
 e
 d
 :
  
 o
 n
 l
 y
  
 1
  
 i
 n
 p
 u
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
 s
 

 +
 +
  
 s
 t
 a
 r
 t
  
 C
 l
 a
 s
 s
 i
 c
  
 F
 W
 H
 M
  
 c
 a
 l
 c
 u
 l
 a
 t
 i
 o
 n
 s
 

  
 +
  
 C
 l
 a
 s
 s
 i
 c
  
 F
 W
 H
 M
  
 d
 o
 n
 e
  
 (
 0
 .
 0
 0
  
 C
 P
 U
  
 s
  
 t
 h
 u
 s
  
 f
 a
 r
 )
 

 +
 +
  
 s
 t
 a
 r
 t
  
 A
 C
 F
  
 c
 a
 l
 c
 u
 l
 a
 t
 i
 o
 n
 s
  
 o
 u
 t
  
 t
 o
  
 r
 a
 d
 i
 u
 s
  
 =
  
 2
 7
 .
 2
 6
  
 m
 m
 

  
 +
  
 A
 C
 F
  
 d
 o
 n
 e
  
 (
 0
 .
 0
 0
  
 C
 P
 U
  
 s
  
 t
 h
 u
 s
  
 f
 a
 r
 )
 

 +
 +
  
 A
 C
 F
  
 1
 D
  
 f
 i
 l
 e
  
 [
 r
 a
 d
 i
 u
 s
  
 A
 C
 F
  
 m
 i
 x
 e
 d
 _
 m
 o
 d
 e
 l
  
 g
 a
 u
 s
 s
 i
 a
 n
 _
 N
 E
 W
 m
 o
 d
 e
 l
 ]
  
 w
 r
 i
 t
 t
 e
 n
  
 t
 o
  
 3
 d
 F
 W
 H
 M
 x
 .
 1
 D
 

 +
 +
  
 1
 d
 p
 l
 o
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
  
 R
 W
 C
  
 e
 t
  
 a
 l
 .
 

 p
 n
 m
 t
 o
 p
 n
 g
 :
  
 4
 0
  
 c
 o
 l
 o
 r
 s
  
 f
 o
 u
 n
 d
 

  
 +
  
 a
 n
 d
  
 1
 d
 p
 l
 o
 t
 -
 e
 d
  
 t
 o
  
 f
 i
 l
 e
  
 3
 d
 F
 W
 H
 M
 x
 .
 1
 D
 .
 p
 n
 g


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

