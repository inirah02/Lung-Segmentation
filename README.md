# Lung Segmentation for RSNA Pneumonia Detection 

## Overview
This project aims to automatically identify lung opacities in chest x-rays for the RSNA Pneumonia Detection. It is based on the work of Kevin Mader for lung segmentation, as part of the Illuminate AI mentorship program

Medical Image Segmentation involves automatically detecting boundaries within images. In this project, we employ a convolutional neural network with U-Net architecture. The training strategy heavily relies on data augmentation to improve the efficiency of available annotated samples.

Two chest x-ray datasets are used for training:
- Montgomery County dataset: Includes manually segmented lung masks.
- Shenzhen Hospital dataset: Manually segmented by Stirenko et al.

The lung segmentation masks from these datasets are dilated to incorporate lung boundary information within the training network, and the images are resized to 512x512 pixels.

## Features
- Automatic lung opacity identification in chest x-rays.
- Utilizes U-Net architecture for medical image segmentation.
- Data augmentation techniques to enhance training efficiency.
- Incorporation of manually segmented lung masks from two datasets.

## Techniques and Concepts Used
- Convolutional Neural Networks (CNNs)
- U-Net Architecture
- Data Augmentation
- Image Preprocessing (Resizing, Dilation)
- Medical Image Segmentation

## How to Run the Notebook
1. Clone the repository to your local machine:

```bash
git clone https://github.com/your_username/repository_name.git

