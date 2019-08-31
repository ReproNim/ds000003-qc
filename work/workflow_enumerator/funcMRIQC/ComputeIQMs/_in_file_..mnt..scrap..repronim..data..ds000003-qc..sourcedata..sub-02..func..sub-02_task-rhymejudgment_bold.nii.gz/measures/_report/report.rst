Node: funcMRIQC (ComputeIQMs (measures (functional)
===================================================


 Hierarchy : workflow_enumerator.funcMRIQC.ComputeIQMs.measures
 Exec ID : measures.a0


Original Inputs
---------------


* direction : all
* fd_thres : 0.2
* in_dvars : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/ComputeDVARS/sub-02_task-rhymejudgment_bold_valid_volreg_dvars.tsv
* in_epi : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/mean/sub-02_task-rhymejudgment_bold_valid_volreg_tstat.nii.gz
* in_fd : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/ComputeFD/fd_power_2012.txt
* in_fwhm : [7.6509, 9.21733, 8.98842, 8.59014]
* in_hmc : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/motion_correct/sub-02_task-rhymejudgment_bold_valid_volreg.nii.gz
* in_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/erode/sub-02_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz
* in_tsnr : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/compute_tsnr/tsnr.nii.gz

Execution Inputs
----------------


* direction : all
* fd_thres : 0.2
* in_dvars : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/ComputeDVARS/sub-02_task-rhymejudgment_bold_valid_volreg_dvars.tsv
* in_epi : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/mean/sub-02_task-rhymejudgment_bold_valid_volreg_tstat.nii.gz
* in_fd : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/ComputeFD/fd_power_2012.txt
* in_fwhm : [7.6509, 9.21733, 8.98842, 8.59014]
* in_hmc : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRI_HMC_afni/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/motion_correct/sub-02_task-rhymejudgment_bold_valid_volreg.nii.gz
* in_mask : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/fMRIBrainMask/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/erode/sub-02_task-rhymejudgment_bold_valid_volreg_tstat_brain_mask_ero.nii.gz
* in_tsnr : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/compute_tsnr/tsnr.nii.gz


Execution Outputs
-----------------


* dvars : <undefined>
* efc : <undefined>
* fber : <undefined>
* fd : <undefined>
* fwhm : <undefined>
* gsr : <undefined>
* out_qc : {'dvars_nstd': 26.91600022113924, 'dvars_std': 1.0369942332911388, 'dvars_vstd': 0.9655337357594933, 'efc': 0.5554955293267978, 'fber': 1956.031982421875, 'fd_mean': 0.15021025188406575, 'fd_num': 31, 'fd_perc': 19.49685534591195, 'fwhm_avg': 2.5483128666666666, 'fwhm_x': 2.448288, 'fwhm_y': 2.9495456, 'fwhm_z': 2.247105, 'gsr_x': -0.0009642474469728768, 'gsr_y': 0.028725383803248405, 'size_t': 159, 'size_x': 64, 'size_y': 64, 'size_z': 33, 'snr': 5.907171750588017, 'spacing_tr': 2.0, 'spacing_x': 3.125, 'spacing_y': 3.125, 'spacing_z': 4.0, 'summary_bg_k': 31.205675882381506, 'summary_bg_mad': 5.837163925170898, 'summary_bg_mean': 29.748321533203125, 'summary_bg_median': 13.817609786987305, 'summary_bg_n': 69405.0, 'summary_bg_p05': 9.05660343170166, 'summary_bg_p95': 109.91823425292978, 'summary_bg_stdv': 44.439918518066406, 'summary_fg_k': 5.344184431437792, 'summary_fg_mad': 80.03256225585938, 'summary_fg_mean': 632.7664184570312, 'summary_fg_median': 643.2389526367188, 'summary_fg_n': 33844.0, 'summary_fg_p05': 448.441796875, 'summary_fg_p95': 773.6053314208983, 'summary_fg_stdv': 108.88957977294922, 'tsnr': 44.49171447753906}
* size : <undefined>
* snr : <undefined>
* spacing : <undefined>
* summary : <undefined>
* tsnr : <undefined>


Runtime info
------------


* duration : 0.69066
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..func..sub-02_task-rhymejudgment_bold.nii.gz/measures


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

