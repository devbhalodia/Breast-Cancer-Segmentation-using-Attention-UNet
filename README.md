# Breast-Cancer-Segmentation-using-Attention-UNet
# Overview
This project focuses on breast cancer segmentation using MRI images and the Attention U-Net model. The goal is to accurately segment tumor regions from MRI scans, aiding in early detection and diagnosis. The project is implemented in Python using PyTorch.

# Dataset
The dataset used is BreastDM, which contains 2D MRI images (JPG format) and corresponding labels (PNG format). The dataset is split into train, validation, and test sets to ensure proper model evaluation.

# Model Architecture
The Attention U-Net model is an extension of the standard U-Net, incorporating attention gates to enhance feature extraction. The key components include:
1. Encoder-decoder architecture
2. Skip connections with attention mechanisms
3. 2D convolutional layers for processing individual MRI slices

# Results 
The model is evaluated using Dice Similarity Coefficient (DSC) and Intersection over Union (IoU). The Attention U-Net outperforms the baseline U-Net by better focusing on tumor regions. I was able to get 99% validation accuracy and 0.9 Mean Intersection over Union. 

  
