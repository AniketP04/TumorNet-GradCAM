# TumorNet-GradCam

This repository explores the fascinating world of brain tumor classification using cutting-edge **Convolutional Neural Networks (CNNs)** 
and **eXplainable Artificial Intelligence (XAI)** techniques.

## Dataset
The dataset can be accessed on Kaggle Brain Tumor MRI Dataset.

The dataset to be utilized contains 3,285 brain MRI scan images categorized into four distinct classes: glioma_tumor, meningioma_tumor, pituitary_tumor, and no_tumor.
![Image](https://github.com/AniketP04/TumorNet-GradCam/blob/main/images/brain_mri.png)

## XAI with Grad-CAM
To make the deep learning model more interpretable and transparent, we implement eXplainable AI (XAI) 
through the use of Grad-CAM (Gradient-weighted Class Activation Mapping). Grad-CAM helps highlight the regions of the brain images 
that significantly contribute to the model's classification decisions. This not only aids in model validation but also provides valuable 
insights to medical professionals.

| Glioma Tumor | Meningioma Tumor | 
| ----------- | ----------- |
| ![Image](https://github.com/AniketP04/TumorNet-GradCam/blob/main/images/glioma_tumor.png) | ![Image](https://github.com/AniketP04/TumorNet-GradCam/blob/main/images/meningioma_tumor.png) |

| No Tumor | Pituitary Tumor |
| ----------- | ----------- |
| ![Image](https://github.com/AniketP04/TumorNet-GradCam/blob/main/images/no_tumor.png) | ![Image](https://github.com/AniketP04/TumorNet-GradCam/blob/main/images/pituitary_tumor.png) |
