Node: anatMRIQCT1w (AirMaskWorkflow (ArtifactMask (anatomical)
==============================================================


 Hierarchy : workflow_enumerator.anatMRIQCT1w.AirMaskWorkflow.ArtifactMask
 Exec ID : ArtifactMask.a1


Original Inputs
---------------


* head_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/HeadMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/fsl_bet/sub-13_T1w_conformed_corrected_brain_outskin_mask.nii.gz
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/conform/sub-13_T1w_conformed.nii.gz
* nasion_post_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AirMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/invert_xfm/tpl-MNI152NLin2009cAsym_res-01_desc-head_mask_trans.nii.gz
* rot_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AirMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/RotationMask/sub-13_T1w_conformed_rotmask.nii.gz

Execution Inputs
----------------


* head_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/HeadMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/fsl_bet/sub-13_T1w_conformed_corrected_brain_outskin_mask.nii.gz
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/conform/sub-13_T1w_conformed.nii.gz
* nasion_post_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AirMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/invert_xfm/tpl-MNI152NLin2009cAsym_res-01_desc-head_mask_trans.nii.gz
* rot_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AirMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/RotationMask/sub-13_T1w_conformed_rotmask.nii.gz


Execution Outputs
-----------------


* out_air_msk : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AirMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/ArtifactMask/sub-13_T1w_conformed_air.nii.gz
* out_art_msk : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AirMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/ArtifactMask/sub-13_T1w_conformed_art.nii.gz
* out_hat_msk : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AirMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/ArtifactMask/sub-13_T1w_conformed_hat.nii.gz


Runtime info
------------


* duration : 2.812107
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AirMaskWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/ArtifactMask


Environment
~~~~~~~~~~~


* AFNI_IMSAVE_WARNINGS : NO
* AFNI_MODELPATH : /opt/afni/models
* AFNI_PLUGINPATH : /opt/afni/plugins
* AFNI_TTATLAS_DATASET : /opt/afni/atlases
* ANTSPATH : /usr/lib/ants
* CPATH : /usr/local/miniconda/include/:
* DATALAD_CONTAINER_NAME : containers/bids-mriqc
* DISPLAY : :5996746
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

