# Models and resources for use in Raidionics and Raidionics-Slicer

All models are in ONNX format, compatible with the latest Raidionics version (v1.2) and Raidionics backend (V1.1.0).

## 1. MRI models
 * Preoperative glioblastoma, diffuse low-grade glioma, meningioma, and metastasis segmentation: the models have been described in [Preoperative Brain Tumor Imaging: Models and Software for Segmentation and Standardized Reporting](https://www.frontiersin.org/articles/10.3389/fneur.2022.932219/full?&utm_source=Email_to_authors_&utm_medium=Email&utm_content=T1_11.5e1_author&utm_campaign=Email_publication&field=&journalName=Frontiers_in_Neurology&id=932219)
 * "_multiclass" models, trained with the AGU-Net architecture over the [BraTS challenges' datasets](https://www.synapse.org/#!Synapse:syn51156910/wiki/), and providing three output labels: contrast-enhancing tumor, necrosis, and edema.

 * Early postoperative glioblastoma segmentation: multiple models leveraging different sets of inputs, introduced in [Segmentation of glioblastomas in early post-operative multi-modal MRI with deep neural networks](https://arxiv.org/abs/2304.08881).

 * Sequence classification: not validated nor introduced in any previous publication yet. Classifies between T1-weighted (T1w), gadolinium-enhanced T1-weighted (T1w-CE), T2-weighted fluid attenuated inversion recovery (FLAIR), and T2-weighted (T2).

## 2. CT models
 * Lymph nodes segmentation: introduced in [Mediastinal lymph nodes segmentation using 3D convolutional neural network ensembles and anatomical priors guiding](https://www.tandfonline.com/doi/pdf/10.1080/21681163.2022.2043778).

 * All other segmentation models: presented in [Semantic segmentation and detection of mediastinal lymph nodes and anatomical structures in CT data for lung cancer staging](https://link.springer.com/article/10.1007/s11548-019-01948-8).
    - CT_PulmSystHeart: segments the heart, the pulmonary trunk, and the pulmonary veins.
    - CT_MediumOrgansMediastinum: segmentas the vena cava, aortic arch, ascending aorta, descending aorta, and spine.
    - CT_SmallOrgansMediastinum: segments the brachiocephalic veins, subclavian and carotid arteries, azygos vein, and esophagus.
    
