# Unet-with-Monuseg-dataset
An implementation of Unet[1] with Monuseg dataset[2]

Background Knowledge:
  Semantic Segmentation Using Deep Learning
  Def: 
      "Semantic Segmentation is about recognizing, understanding what is in the image at pixel level"

Dataset:

Introduction
The dataset for this challenge was obtained by carefully annotating tissue images of several patients with tumors of different organs and who were diagnosed at multiple hospitals. This dataset was created by downloading H&E stained tissue images captured at 40x magnification from TCGA archive. H&E staining is a routine protocol to enhance the contrast of a tissue section and is commonly used for tumor assessment (grading, staging, etc.). Given the diversity of nuclei appearances across multiple organs and patients, and the richness of staining protocols adopted at multiple hospitals, the training datatset will enable the development of robust and generalizable nuclei segmentation techniques that will work right out of the box.

Training Data
Training data containing 30 images and around 22,000 nuclear boundary annotations has been released to the public previously as a dataset article in IEEE Transactions on Medical imaging in 2017.

Testing Data
Test set images with additional 7000 nuclear boundary annotations are available here MoNuSeg 2018 Testing data[3].


[1]  https://github.com/hlamba28/UNET-TGS
[2]  https://monuseg.grand-challenge.org/Data/
[3]  https://drive.google.com/file/d/1NKkSQ5T0ZNQ8aUhh0a8Dt2YKYCQXIViw/view
