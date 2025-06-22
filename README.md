# LinTUNet: A Hybrid Sparse Transformer-CNN Architecture for Brain Tumor Segmentation

LinTUNet is a hybrid model combining the power of Sparse Transformer-based attention mechanisms with CNN-based architectures, specifically designed to improve brain tumor segmentation from MRI scans. This architecture leverages sparse self-attention using the **Sparse Linformer** to enhance feature extraction and capture long-range dependencies in medical images. The model is implemented and executed in a Jupyter Notebook using Google Colab.

## Overview

In medical imaging, brain tumor segmentation plays a crucial role in accurately identifying tumor regions in MRI scans. Traditional CNN-based models like U-Net are widely used for segmentation tasks but often struggle with capturing long-range dependencies and irregular tumor shapes. To overcome these challenges, **LinTUNet** integrates Transformer-based attention into the U-Net architecture, providing a more efficient and accurate solution.

### Key Features:
- **Hybrid CNN-Transformer architecture**: Combines U-Net's effective feature extraction with a Transformer layer for enhanced long-range dependency modeling.
- **Sparse Self-Attention with Sparse Linformer**: Implements a Sparse Linformer for computationally efficient attention mechanisms.
- **Improved segmentation accuracy**: LinTUNet outperforms traditional U-Net models in key segmentation metrics such as IoU (Intersection over Union) and F1-score.

# Data Preprocessing and Model Setup

This project is designed to load, preprocess, and prepare image segmentation datasets for model training. It utilizes Google Colab and the Google Drive API for file handling.

## Prerequisites
1. **Google Drive**: The dataset must be uploaded to your Google Drive.
2. **Notebook Setup**: The following steps need to be executed in a Google Colab notebook.

## Steps to Run the Notebook

### Step 1: Upload the Data to Google Drive
- Download the dataset file `Data.zip` from the kaggle dataset and upload it to your Google Drive, preferably in the directory: `MyDrive/.
- Ensure that the dataset contains the folders `train`, `test`, and `valid`, and the associated annotation files for each.

### Step 2: Mount Google Drive in Colab
First, mount Google Drive to access your files:

from google.colab import drive
drive.mount('/content/drive')

### Step 3: Run the Notebook
once this is all set up run the notebook and everything will run automatically. 




## Publication

The development of **LinTUNet** is inspired by the paper:

**Title**: LinTUNet: A Hybrid Transformer-CNN Architecture for Brain Tumor Segmentation  

**Authors**: Lawrence Menegus, DongSheng Che

**Published in**: PACISE Conference  

**Year**: 2025


## Contributors: 
Lawrence Menegus 
