# Lightweight Multidimensional Feature Enhancement Algorithm LPS-YOLO for UAV Remote Sensing Target Detection
This repository contains a selection of experimental data used to validate the results presented in our research paper on LPS-YOLO. The data are organised in a manner that facilitates convenient access and validation of the results, as they are stored in a format that includes the training and validation outputs of various YOLO-based models. Furthermore, we provide download links to the open source datasets used in this repository.


Please note that the original link, https://github.com/23302093/LPS-YOLO-Training-dataset-and-experimental-result-data-repository, is no longer valid, as the account in question has been frozen and is therefore unavailable. We have also optimised the data structure for easier viewing.


## Abstract
{Detecting small targets in UAV remote sensing images is challenging for traditional lightweight methods due to difficulty in feature extraction and high background interference. We propose LPS-YOLO, which improves small target feature extraction while reducing computational complexity. Replacing the Conv backbone with SPDConv to retain fine-grained features, introduces the SKAPP module for better feature fusion, and incorporates the E-BiFPN and OFTP structures to efficiently preserve and transfer backbone information. Evaluation on the VisDrone2019 dataset shows a 17.3% increase in mean Average Precision (mAP) and a 42.5% reduction in parameters compared to the baseline. Additional experiments on the DOTAv2 dataset demonstrate the model’s robustness, with a 14.5% improvement in F1 score and a 14.9% increase in mAP over YOLOv8-n. LPS-YOLO offers an effective solution for multi-target detection in UAVs. 

![Overview of the structure of LPS-YOLO](/images/LPS-YOLO.png)

## Repository Structure

The repository is structured into two main directories, each containing data from different phases of model evaluation:

### 1. Screenshot of experimental data

This directory contains the results from the training phase of the models. It is subdivided into three specific subdirectories:

- **Ablation**: Screenshots of the resultant data from the ablation experiments in the paper are provided.

- **Train**: This directory is used to store screenshots of training result data for some of the models from the two open-source datasets.
- ***VisDrone***
- ***DOTAv2***
  
- **Val**: This directory is used to store screenshots of value result data for some of the models from the two open-source datasets.
- ***VisDrone***
- ***DOTAv2***

## Experimental Datasets
 **DataSets**：The experimental datasets we used are two open source datasets:
   - **VisDrone2019**: https://github.com/VisDrone/VisDrone-Dataset
   - **Dotav2**: https://github.com/ultralytics/yolov5/releases/download/v1.0/DOTAv2.zip

## Citation

If you find this repository useful in your research, please consider citing our paper:

