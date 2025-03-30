# 3D Liver Tumor Segmentation

Author: Mateusz Pilch

### Overview
This project focuses on comparing different deep learning models for liver cancer segmentation using 3D CT scans. The primary goal is to evaluate how well various architectures perform in detecting cancerous tissues within CT images, where each image is labeled with three categories: non-organ, healthy tissue, and cancerous tissue. The dataset consists of 3D CT scans, and the comparison will be made based on various performance metrics.

### Models 
- U-Net++

### Metrics
- Dice Loss
- mIoU (Mean Intersection over Union)
- PA (Pixel Accuracy)

### Libraries
- PyTorch
- NumPy
- Segmentation_models_pytorch (smp)
- Albumentations
- Nibabel
- Matplotlib

### Dataset
https://www.kaggle.com/datasets/prathamgrover/3d-liver-segmentation/data 