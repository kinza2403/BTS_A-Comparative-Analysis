# BTS_A-Comparative-Analysis
This repository holds the survey of deep learning models being used for Brain Tumor Segmentation along with a comparative analysis of models

The paper discusses the details of Brain tumor tissue types, Glioma Tumor Analysis, the major challenges that are faced while performing tumor segmentation task. It gives the description of existing models focusing on both CNN approaches and integrated models of CNN and Transformers. The paper descibes the overview of deep models used for comparative study and conlcuding with the implementation results on Brain dataset.

# Dataset
The data used in this work is MICCAI BraTS 2019 Training and Vaidation sets , can be requested and downloaded from this link: https://ipp.cbica.upenn.edu/categories/brats2019

# Training & Testing
Sample notebooks for training and sample testing of the models are provided in Models folder. Data is required to be stored in the Drive folder before executing the notebooks.

# Results
The visualizations of segmentation results of each model can be reviewed from Results folder
The comparative results can be reviewed from the tables below:

Table I : Brain Tumor Segmentation Comparative Analysis Results on BraTS dataset

![result1](https://user-images.githubusercontent.com/90093202/162196739-901cf86c-3e2a-4873-9c25-98c608e19989.png)

## DeepMedic
DeepMedic is the software that allows to train a deep learning model and obtain the segmentation results. Initially, it was used for segmenting brain lesions in MRI imaging modality. It allows multi scale processing of multi modal data more efficiently. The software requires the preprocessing of medical images and accepts the data in form of NIFTI files. The preprocessing of the data involves normalizing the data and obtaining ROI masks including brain masks. The software is yet being developed and can be used as a baseline for fulfilling medical segmentation tasks.

Table II : DeepMedic Multimodal Segmentation results at each label obtained on BraTS dataset

![result2](https://user-images.githubusercontent.com/90093202/162196789-26b4eafb-31f9-4eab-ba5d-18e2da46fb37.png)
