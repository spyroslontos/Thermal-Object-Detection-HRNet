# Thermal Object Detection with High-Resolution Networks

*MSc Dissertation Project*

This project investigates the effectiveness of High-Resolution Networks (HRNet) for object detection in thermal imagery, comparing performance against traditional ResNet backbones. Using the MMDetection framework, Faster R-CNN models with different HRNet configurations were trained and evaluated on the FLIR ADAS thermal dataset.

The research demonstrates that HRNet backbones can significantly improve thermal object detection performance, with the HRNet-W40 configuration achieving a 7% improvement over the baseline ResNet-50-FPN backbone.

📄 **[Full Dissertation Report (PDF)](./MSc_Dissertation_HRNet_FLIR.pdf)**

---

## Overview

- **Model**: Faster R-CNN with HRNet backbones  
- **Dataset**: FLIR ADAS thermal dataset (cars, people, bicycles)  
- **Framework**: MMDetection  
- **Pre-training**: COCO 2017 dataset  
- **Performance**: 7% improvement over ResNet-50-FPN baseline  
- **Best Configuration**: HRNet-W40  

---

## Data & Models

Due to storage limitations, trained models and datasets are no longer hosted.  
This repository includes the full codebase and notebooks, but you will need to provide your own dataset and train models locally.

- **Dataset**: Download the FLIR ADAS thermal dataset from the [official site](https://www.flir.com/oem/adas/adas-dataset-form/).  
- **Pre-trained backbones**: HRNet and ResNet weights can be obtained from the [MMDetection model zoo](https://github.com/open-mmlab/mmdetection/blob/main/docs/en/model_zoo.md).  
- **Trained models**: Not distributed anymore — please retrain using the provided configs and scripts.  

---

## Project Structure

```text
project_root/
├── mmdetection/          # MMDetection framework
├── models/               # Placeholder for trained models (if you train locally)
├── train/                # Training dataset
├── val/                  # Validation dataset
├── video/                # Test dataset
├── 1_Dataset_Processing.ipynb
└── 2_Main.ipynb
```

## Notebooks

| Notebook | Description | GitHub |
|----------|-------------|--------|
| Dataset Processing | Dataset processing and annotation preparation | [![Open In GitHub](https://img.shields.io/badge/GitHub-Dataset_Processing-green?logo=github)](https://github.com/Spyroslon/Thermal-Object-Detection-HRNet/blob/main/1_Dataset_Processing.ipynb) |
| Main | Training, visualization, and testing | [![Open In GitHub](https://img.shields.io/badge/GitHub-Main-green?logo=github)](https://github.com/Spyroslon/Thermal-Object-Detection-HRNet/blob/main/2_Main.ipynb) |

**Note**: The structure above mirrors the original Colab/Drive setup. You can adapt paths to your local environment as needed.

---

*This project was developed as part of an MSc dissertation focusing on advancing thermal object detection using state-of-the-art deep learning architectures.*
