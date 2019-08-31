Node: funcMRIQC (ComputeIQMs (ComputeDVARS (confounds)
======================================================


 Hierarchy : workflow_enumerator.funcMRIQC.ComputeIQMs.ComputeDVARS
 Exec ID : ComputeDVARS.a1


Original Inputs
---------------


* figdpi : 100
* figformat : png
* figsize : (11.7, 2.3)
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/motion_correct/sub-13_task-rhymejudgment_bold_valid_volreg.nii.gz
* in_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/erode/sub-13_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz
* intensity_normalization : 1000.0
* remove_zerovariance : True
* save_all : True
* save_nstd : False
* save_plot : False
* save_std : True
* save_vxstd : False
* series_tr : <undefined>

Execution Inputs
----------------


* figdpi : 100
* figformat : png
* figsize : (11.7, 2.3)
* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/motion_correct/sub-13_task-rhymejudgment_bold_valid_volreg.nii.gz
* in_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/erode/sub-13_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz
* intensity_normalization : 1000.0
* remove_zerovariance : True
* save_all : True
* save_nstd : False
* save_plot : False
* save_std : True
* save_vxstd : False
* series_tr : <undefined>


Execution Outputs
-----------------


* avg_nstd : <undefined>
* avg_std : <undefined>
* avg_vxstd : <undefined>
* fig_nstd : <undefined>
* fig_std : <undefined>
* fig_vxstd : <undefined>
* out_all : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/ComputeDVARS/sub-13_task-rhymejudgment_bold_valid_volreg_dvars.tsv
* out_nstd : <undefined>
* out_std : <undefined>
* out_vxstd : <undefined>


Runtime info
------------


* duration : 13.856746
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/ComputeDVARS


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

