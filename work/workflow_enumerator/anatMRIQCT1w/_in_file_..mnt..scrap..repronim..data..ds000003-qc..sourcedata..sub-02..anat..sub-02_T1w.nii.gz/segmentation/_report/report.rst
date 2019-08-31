Node: anatMRIQCT1w (segmentation (fsl)
======================================


 Hierarchy : workflow_enumerator.anatMRIQCT1w.segmentation
 Exec ID : segmentation.a0


Original Inputs
---------------


* args : <undefined>
* bias_iters : <undefined>
* bias_lowpass : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* hyper : <undefined>
* img_type : 1
* in_files : ['/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/AFNISkullStripWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/sstrip_orig_vol/sub-02_T1w_conformed_calc.nii.gz']
* init_seg_smooth : <undefined>
* init_transform : <undefined>
* iters_afterbias : <undefined>
* manual_seg : <undefined>
* mixel_smooth : <undefined>
* no_bias : <undefined>
* no_pve : <undefined>
* number_classes : <undefined>
* other_priors : <undefined>
* out_basename : segment
* output_biascorrected : <undefined>
* output_biasfield : <undefined>
* output_type : NIFTI_GZ
* probability_maps : <undefined>
* segment_iters : <undefined>
* segments : True
* use_priors : <undefined>
* verbose : <undefined>

Execution Inputs
----------------


* args : <undefined>
* bias_iters : <undefined>
* bias_lowpass : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* hyper : <undefined>
* img_type : 1
* in_files : ['/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/segmentation/sub-02_T1w_conformed_calc.nii.gz']
* init_seg_smooth : <undefined>
* init_transform : <undefined>
* iters_afterbias : <undefined>
* manual_seg : <undefined>
* mixel_smooth : <undefined>
* no_bias : <undefined>
* no_pve : <undefined>
* number_classes : <undefined>
* other_priors : <undefined>
* out_basename : segment
* output_biascorrected : <undefined>
* output_biasfield : <undefined>
* output_type : NIFTI_GZ
* probability_maps : <undefined>
* segment_iters : <undefined>
* segments : True
* use_priors : <undefined>
* verbose : <undefined>


Execution Outputs
-----------------


* bias_field : <undefined>
* mixeltype : <undefined>
* partial_volume_files : ['/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/segmentation/segment_pve_0.nii.gz', '/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/segmentation/segment_pve_1.nii.gz', '/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/segmentation/segment_pve_2.nii.gz']
* partial_volume_map : <undefined>
* probability_maps : <undefined>
* restored_image : <undefined>
* tissue_class_files : <undefined>
* tissue_class_map : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/segmentation/segment_seg.nii.gz


Runtime info
------------


* command : fast -t 1 -o segment -g -S 1 /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/segmentation/sub-02_T1w_conformed_calc.nii.gz
* duration : 165.547113
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-02..anat..sub-02_T1w.nii.gz/segmentation


Terminal output
~~~~~~~~~~~~~~~





Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~





Terminal - standard error
~~~~~~~~~~~~~~~~~~~~~~~~~





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

