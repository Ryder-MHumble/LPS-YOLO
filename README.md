# Lightweight Multidimensional Feature Enhancement Algorithm LPS-YOLO for UAV Remote Sensing Target Detection

This repository contains experimental data and results validating the LPS-YOLO algorithm presented in our research paper. The data is organized to facilitate easy access and validation, including training and validation outputs from various YOLO-based models. We also provide download links to the open source datasets used in our experiments.

Note: The original repository link (https://github.com/23302093/LPS-YOLO-Training-dataset-and-experimental-result-data-repository) is no longer accessible due to account suspension. We have reorganized and optimized the data structure for better accessibility.

## Abstract

Small target detection in UAV remote sensing images poses significant challenges for traditional lightweight methods due to difficulties in feature extraction and high background interference. To address these challenges, we propose LPS-YOLO, a novel approach that enhances small target feature extraction while reducing computational complexity. Key innovations include:

- Replacing conventional Conv backbone with SPDConv to preserve fine-grained features
- Introducing SKAPP module for improved feature fusion 
- Incorporating E-BiFPN and OFTP structures for efficient backbone information preservation and transfer

Our evaluation on the VisDrone2019 dataset demonstrates:
- 17.3% increase in mean Average Precision (mAP)
- 42.5% reduction in parameters compared to baseline

Additional experiments on DOTAv2 dataset show:
- 14.5% improvement in F1 score
- 14.9% increase in mAP over YOLOv8-n

These results establish LPS-YOLO as an effective solution for multi-target detection in UAV applications.

![Overview of the structure of LPS-YOLO](/images/LPS-YOLO.png)

## Repository Structure

The repository is organized into two main sections:

### 1. Experimental Results Screenshots

Contains comprehensive evaluation data organized into:

- **Ablation Studies**: Screenshots documenting ablation experiment results
- **Training Results**: Model training outcomes for both datasets:
  - *VisDrone*
  - *DOTAv2*
- **Validation Results**: Model validation data for both datasets:
  - *VisDrone*
  - *DOTAv2*

## Datasets

Our experiments utilize two widely-recognized open source datasets:

- **VisDrone2019**: [https://github.com/VisDrone/VisDrone-Dataset](https://github.com/VisDrone/VisDrone-Dataset)
- **DOTAv2**: [https://github.com/ultralytics/yolov5/releases/download/v1.0/DOTAv2.zip](https://github.com/ultralytics/yolov5/releases/download/v1.0/DOTAv2.zip)

## Citation

If you find this work helpful for your research, please consider citing our paper:
```json
@article{lu2025lightweight,
  title={Lightweight multidimensional feature enhancement algorithm LPS-YOLO for UAV remote sensing target detection},
  author={Lu, Yong and Sun, Minghao},
  journal={Scientific Reports},
  volume={15},
  number={1},
  pages={1340},
  year={2025},
  publisher={Nature Publishing Group UK London}
}
```
