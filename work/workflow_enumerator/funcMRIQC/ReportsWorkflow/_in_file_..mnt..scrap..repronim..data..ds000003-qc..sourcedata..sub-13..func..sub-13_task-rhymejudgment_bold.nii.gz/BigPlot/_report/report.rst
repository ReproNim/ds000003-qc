Node: funcMRIQC (ReportsWorkflow (BigPlot (plotting)
====================================================


 Hierarchy : workflow_enumerator.funcMRIQC.ReportsWorkflow.BigPlot
 Exec ID : BigPlot.a1


Original Inputs
---------------


* dvars : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/ComputeDVARS/sub-13_task-rhymejudgment_bold_valid_volreg_dvars.tsv
* fd : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/ComputeFD/fd_power_2012.txt
* fd_thres : 0.2
* in_func : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/motion_correct/sub-13_task-rhymejudgment_bold_valid_volreg.nii.gz
* in_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/erode/sub-13_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz
* in_segm : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/ResampleSegmentation/tpl-MNI152NLin2009cAsym_res-01_desc-carpet_dseg_trans.nii.gz
* in_spikes_bg : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/SpikesFinderBgMask/spikes_tsz.txt
* outliers : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/outliers/outliers.out
* tr : None

Execution Inputs
----------------


* dvars : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/ComputeDVARS/sub-13_task-rhymejudgment_bold_valid_volreg_dvars.tsv
* fd : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/ComputeFD/fd_power_2012.txt
* fd_thres : 0.2
* in_func : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/motion_correct/sub-13_task-rhymejudgment_bold_valid_volreg.nii.gz
* in_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/erode/sub-13_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz
* in_segm : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/ResampleSegmentation/tpl-MNI152NLin2009cAsym_res-01_desc-carpet_dseg_trans.nii.gz
* in_spikes_bg : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/SpikesFinderBgMask/spikes_tsz.txt
* outliers : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/outliers/outliers.out
* tr : None


Execution Outputs
-----------------


* out_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/BigPlot/sub-13_task-rhymejudgment_bold_valid_volreg_fmriplot.svg


Runtime info
------------


* duration : 2.576036
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/BigPlot


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

