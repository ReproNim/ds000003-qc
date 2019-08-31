Node: ants
==========


 Hierarchy : _MNItpms2t10
 Exec ID : _MNItpms2t10


Original Inputs
---------------


* args : <undefined>
* default_value : 0.0
* dimension : 3
* environ : {'NSLOTS': '1'}
* float : True
* input_image : /home/bidsapp/.cache/templateflow/tpl-MNI152NLin2009cAsym/tpl-MNI152NLin2009cAsym_res-01_label-CSF_probseg.nii.gz
* input_image_type : <undefined>
* interpolation : Linear
* interpolation_parameters : <undefined>
* invert_transform_flags : <undefined>
* num_threads : 1
* out_postfix : _trans
* output_image : <undefined>
* print_out_composite_warp_file : <undefined>
* reference_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/conform/sub-13_T1w_conformed.nii.gz
* transforms : ['/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/SpatialNormalization/ants_t1_to_mniInverseComposite.h5']

Execution Inputs
----------------


* args : <undefined>
* default_value : 0.0
* dimension : 3
* environ : {'NSLOTS': '1'}
* float : True
* input_image : /home/bidsapp/.cache/templateflow/tpl-MNI152NLin2009cAsym/tpl-MNI152NLin2009cAsym_res-01_label-CSF_probseg.nii.gz
* input_image_type : <undefined>
* interpolation : Linear
* interpolation_parameters : <undefined>
* invert_transform_flags : <undefined>
* num_threads : 1
* out_postfix : _trans
* output_image : <undefined>
* print_out_composite_warp_file : <undefined>
* reference_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/conform/sub-13_T1w_conformed.nii.gz
* transforms : ['/mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/SpatialNormalization/ants_t1_to_mniInverseComposite.h5']


Execution Outputs
-----------------


* output_image : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/MNItpms2t1/mapflow/_MNItpms2t10/tpl-MNI152NLin2009cAsym_res-01_label-CSF_probseg_trans.nii.gz


Runtime info
------------


* command : antsApplyTransforms --default-value 0 --dimensionality 3 --float 1 --input /home/bidsapp/.cache/templateflow/tpl-MNI152NLin2009cAsym/tpl-MNI152NLin2009cAsym_res-01_label-CSF_probseg.nii.gz --interpolation Linear --output tpl-MNI152NLin2009cAsym_res-01_label-CSF_probseg_trans.nii.gz --reference-image /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/conform/sub-13_T1w_conformed.nii.gz --transform /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/SpatialNormalization/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/SpatialNormalization/ants_t1_to_mniInverseComposite.h5
* duration : 2.326088
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/anatMRIQCT1w/ComputeIQMs/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..anat..sub-13_T1w.nii.gz/MNItpms2t1/mapflow/_MNItpms2t10


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
* NSLOTS : 1
* OMP_NUM_THREADS : 1
* PATH : /usr/local/miniconda/bin:/opt/afni:/usr/lib/ants:/usr/lib/fsl/5.0:/usr/lib/afni/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
* POSSUMDIR : /usr/share/fsl/5.0
* PS1 : Singularity> 
* PWD : /mnt/scrap/repronim/data/ds000003-qc
* PYTHONNOUSERSITE : 1
* SINGULARITY_CONTAINER : MD5E-s2914574367--827e2277cfe2e482546b18535ca18251.1.sing
* SINGULARITY_NAME : MD5E-s2914574367--827e2277cfe2e482546b18535ca18251.1.sing
* TERM : screen

