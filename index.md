
## Portfolio 

### [Pipeline for automatic preprocessing of clinical MRI images]([to be added])
<br><br>
Image-based mathematical models rely on preprocessed clinical data for generating the target quantitative maps per patient and therefore pipelines are necessary to automate and streamline preprocessing steps. In this project, I developed a python-based pipeline to preprocess MRI images for use in tumor edema maps. Given a pair of MRI images with T1W with gadolinium contrast (T1Gd) and fluid attenuated inversion recovery (FLAIR) sequence types, this pipeline automatically conducts some of the preprocessing steps including resampling, resizing, denoising, bias field correction, and tissue segmentation. Brain and tumor delineation are postprocessed to match the original image dimension and voxel size.

<img src="images/pipeline.png?raw=false"/>

---
### [Predicting spatial heterogeneity within GBMs]([https://github.com/SARARANJBAR/SpatialHeterogeneityPredictor])
The aim of the project is to build a machine learning model to predict the abbundance of ki67 (a known marker of proliferation) in MRI-localized biopsies from features describing imaging patterns around the biopsies.

Predicting ki67 is useful to identify if imaging patterns explain proliferation is biospy samples. We know that proliferation is elevated where tumor cells are present. If we can predict where proliferation happens, we can basically create maps corresponding to the spatial distribution of proliferation across whole tumors. Such maps can potentially inform radiation planning to target areas where the tumor shows maximal activity.

---
### [Developing a CNN for classifiaction of MRI sequence types]([https://github.com/SARARANJBAR/PNTGliomaSegmentationProjec])

One factor affecting the ability to aggregate large medical image collections for research is the lack of infrastructure for automated data annotation. Among all imaging modalities, annotation of magnetic resonance (MR) images is particularly challenging due to the non-standard labeling of MR image types. In this work, we aimed to train a deep neural network to annotate MR image sequence type for scans of brain tumor patients. We focused on the four most common MR sequence types within neuroimaging: T1-weighted (T1W), T1-weighted post-gadolinium contrast (T1Gd), T2-weighted (T2W), and T2-weighted fluid-attenuated inversion recovery (FLAIR).
<img src="images/seqpred.png?raw=true"/>

### [predicting sex-specific glioma tissue state transition from imaging patterns]([https://github.com/SARARANJBAR/PNTGliomaBiopsyMachineLearningProject])
---



