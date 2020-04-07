# Advance Computer Vision Projects
Repository contains ACV projects of Semantic Segmentation

# Background Knowledge:
  Def: 
      >"Semantic Segmentation is about recognizing, understanding what is in the image at pixel level"
      as shown in the image below
      ![](Images/Segmentation%20Sample.png)
# Why
  * To learn about the semantic segmentation pipeline
  * Implementation of semantic segmentation pipeline on a real world dataset
      
# Tools Used
  * [PyCharm](https://www.jetbrains.com/pycharm/)
  * [Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb)
  * [Microsoft Azure](https://azure.microsoft.com/en-au/)
 
# Language Used
  * Python 3.6

# Dataset Used:

## Introduction

The dataset for this challenge was obtained by carefully annotating tissue images of several patients with tumors of different organs and who were diagnosed at multiple hospitals. This dataset was created by downloading H&E stained tissue images captured at 40x magnification from TCGA archive. H&E staining is a routine protocol to enhance the contrast of a tissue section and is commonly used for tumor assessment (grading, staging, etc.). Given the diversity of nuclei appearances across multiple organs and patients, and the richness of staining protocols adopted at multiple hospitals, the training datatset will enable the development of robust and generalizable nuclei segmentation techniques that will work right out of the box.
A Dataset of tissue images can be retrieved directle from challenge [website](https://monuseg.grand-challenge.org/Data/) or [drive](https://drive.google.com/file/d/1NKkSQ5T0ZNQ8aUhh0a8Dt2YKYCQXIViw/view).

## Training Data

Training data containing 30 images and around 22,000 nuclear boundary annotations has been released to the public previously as a dataset article in IEEE Transactions on Medical imaging in 2017.

## Testing Data

Test set images with additional 7000 nuclear boundary annotations are available here MoNuSeg 2018 Testing data[3].

For Model Summary along with pretrained weights please refer "Unet with MonuSeg dataset.ipynb"

# Implemented Architectures

* [Contribution guidelines for **UNet**](U-Net/)
* [Contribution guidelines for **Segnet**](Seg-Net/)
* [Contribution guidelines for **DeepNet**](Deep-Net/)

# Author
-Asmat Zahra
