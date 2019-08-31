Node: funcMRIQC (ReportsWorkflow (SpikesMask (utility)
======================================================


 Hierarchy : workflow_enumerator.funcMRIQC.ReportsWorkflow.SpikesMask
 Exec ID : SpikesMask.a1


Original Inputs
---------------


* function_str : def spikes_mask(in_file, in_mask=None, out_file=None):
    """
    Utility function to calculate a mask in which check
    for :abbr:`EM (electromagnetic)` spikes.
    """

    import os.path as op
    import nibabel as nb
    import numpy as np
    from nilearn.image import mean_img
    from nilearn.plotting import plot_roi
    from scipy import ndimage as nd

    if out_file is None:
        fname, ext = op.splitext(op.basename(in_file))
        if ext == '.gz':
            fname, ext2 = op.splitext(fname)
            ext = ext2 + ext
        out_file = op.abspath('{}_spmask{}'.format(fname, ext))
        out_plot = op.abspath('{}_spmask.pdf'.format(fname))

    in_4d_nii = nb.load(in_file)
    orientation = nb.aff2axcodes(in_4d_nii.affine)

    if in_mask:
        mask_data = nb.load(in_mask).get_data()
        a = np.where(mask_data != 0)
        bbox = np.max(a[0]) - np.min(a[0]), np.max(a[1]) - \
            np.min(a[1]), np.max(a[2]) - np.min(a[2])
        longest_axis = np.argmax(bbox)

        # Input here is a binarized and intersected mask data from previous section
        dil_mask = nd.binary_dilation(
            mask_data, iterations=int(mask_data.shape[longest_axis] / 9))

        rep = list(mask_data.shape)
        rep[longest_axis] = -1
        new_mask_2d = dil_mask.max(axis=longest_axis).reshape(rep)

        rep = [1, 1, 1]
        rep[longest_axis] = mask_data.shape[longest_axis]
        new_mask_3d = np.logical_not(np.tile(new_mask_2d, rep))
    else:
        new_mask_3d = np.zeros(in_4d_nii.shape[:3]) == 1

    if orientation[0] in ['L', 'R']:
        new_mask_3d[0:2, :, :] = True
        new_mask_3d[-3:-1, :, :] = True
    else:
        new_mask_3d[:, 0:2, :] = True
        new_mask_3d[:, -3:-1, :] = True

    mask_nii = nb.Nifti1Image(new_mask_3d.astype(np.uint8), in_4d_nii.affine,
                              in_4d_nii.header)
    mask_nii.to_filename(out_file)

    plot_roi(mask_nii, mean_img(in_4d_nii), output_file=out_plot)
    return out_file, out_plot

* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/sanitize/sub-13_task-rhymejudgment_bold_valid.nii.gz
* in_mask : <undefined>

Execution Inputs
----------------


* function_str : def spikes_mask(in_file, in_mask=None, out_file=None):
    """
    Utility function to calculate a mask in which check
    for :abbr:`EM (electromagnetic)` spikes.
    """

    import os.path as op
    import nibabel as nb
    import numpy as np
    from nilearn.image import mean_img
    from nilearn.plotting import plot_roi
    from scipy import ndimage as nd

    if out_file is None:
        fname, ext = op.splitext(op.basename(in_file))
        if ext == '.gz':
            fname, ext2 = op.splitext(fname)
            ext = ext2 + ext
        out_file = op.abspath('{}_spmask{}'.format(fname, ext))
        out_plot = op.abspath('{}_spmask.pdf'.format(fname))

    in_4d_nii = nb.load(in_file)
    orientation = nb.aff2axcodes(in_4d_nii.affine)

    if in_mask:
        mask_data = nb.load(in_mask).get_data()
        a = np.where(mask_data != 0)
        bbox = np.max(a[0]) - np.min(a[0]), np.max(a[1]) - \
            np.min(a[1]), np.max(a[2]) - np.min(a[2])
        longest_axis = np.argmax(bbox)

        # Input here is a binarized and intersected mask data from previous section
        dil_mask = nd.binary_dilation(
            mask_data, iterations=int(mask_data.shape[longest_axis] / 9))

        rep = list(mask_data.shape)
        rep[longest_axis] = -1
        new_mask_2d = dil_mask.max(axis=longest_axis).reshape(rep)

        rep = [1, 1, 1]
        rep[longest_axis] = mask_data.shape[longest_axis]
        new_mask_3d = np.logical_not(np.tile(new_mask_2d, rep))
    else:
        new_mask_3d = np.zeros(in_4d_nii.shape[:3]) == 1

    if orientation[0] in ['L', 'R']:
        new_mask_3d[0:2, :, :] = True
        new_mask_3d[-3:-1, :, :] = True
    else:
        new_mask_3d[:, 0:2, :] = True
        new_mask_3d[:, -3:-1, :] = True

    mask_nii = nb.Nifti1Image(new_mask_3d.astype(np.uint8), in_4d_nii.affine,
                              in_4d_nii.header)
    mask_nii.to_filename(out_file)

    plot_roi(mask_nii, mean_img(in_4d_nii), output_file=out_plot)
    return out_file, out_plot

* in_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/sanitize/sub-13_task-rhymejudgment_bold_valid.nii.gz
* in_mask : <undefined>


Execution Outputs
-----------------


* out_file : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/SpikesMask/sub-13_task-rhymejudgment_bold_valid_spmask.nii.gz
* out_plot : <undefined>


Runtime info
------------


* duration : 2.1229459999999998
* hostname : smaug
* prev_wd : /mnt/scrap/repronim/data/ds000003-qc
* working_dir : /mnt/scrap/repronim/data/ds000003-qc/work/workflow_enumerator/funcMRIQC/ReportsWorkflow/_in_file_..mnt..scrap..repronim..data..ds000003-qc..sourcedata..sub-13..func..sub-13_task-rhymejudgment_bold.nii.gz/SpikesMask


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

