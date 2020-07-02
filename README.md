# Brain Tumor Diagnosis using Deep Learning

**Dataset used:** https://figshare.com/articles/brain_tumor_dataset/1512427

**Model used:** AlexNet

**Trained on:** Google Colab


## Problem Statement

Building a deep learning model which can identify which kind of tumor exists in the brain.
The model is supposed to classify between: Meningloma, Glioma and Pitutary Tumors.

## Dataset

Form the dataset mentioned above, we are using 2440 images as training set and rest 660 images as validation set. The dataset consists of 708 images for Meningloma,
1146 images for Glioma and 915 images for Pitutary Tumor. Also, the images are of three different views: Sagittal, Axial and Coronal. We have to train a model that
can detect tumors accurately despite the views.

## Solution

Our model is an implementation of AlexNet with 3 convolutoin layers and then 3 fully connected layers, as mentioned below:
