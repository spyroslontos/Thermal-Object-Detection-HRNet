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

## Quick Start

1. Download the entire folder from [Google Drive](https://drive.google.com/drive/folders/1dkl-PlM4f1LQPTWcBINHlPtJxvYcHSEw?usp=sharing) (3.40 GB)
2. Upload to your personal Google Drive
3. Mount your Google Drive in Google Colab
4. Run the notebooks

## Project Structure

```text
Google Drive/
├── mmdetection/          # MMDetection framework
├── models/               # 4 trained models with logs and configs
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

**Note**: For the full pipeline with data, use the Google Drive folder linked above.

---

*This project was developed as part of an MSc dissertation focusing on advancing thermal object detection using state-of-the-art deep learning architectures.*
