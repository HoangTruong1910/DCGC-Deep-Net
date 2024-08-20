# Polyp Segmentation use my model in Kvasir SEG Dataset
## Overview
This repository contains the implementation of binary segmentation models for detecting polyps in small intestine images. The project leverages the Kvasir dataset, which provides a rich collection of annotated endoscopic images. Accurate segmentation of polyps is crucial for early diagnosis and treatment of gastrointestinal diseases.

## Dataset
- **Dataset**: Kvasir SEG
- **Description**: The Kvasir dataset includes a variety of annotated images from gastrointestinal examinations. For this project, we focus on the polyp images, where each image is paired with a ground truth mask indicating the polyp region.
## Approach
- The approach involves training deep learning models to perform binary segmentation of polyps in the provided images. The models are evaluated based on metrics like Dice coefficient, Intersection over Union (IoU), and accuracy to ensure reliable segmentation results.

## DCGC Deep Net Architecture
![DCGC_Deep_Net](https://github.com/user-attachments/assets/c8d0aa48-5cd9-4124-8382-eab451c41fee)

## Residual Block
![Residual_Block](https://github.com/user-attachments/assets/ae5e8a91-bee1-4d5b-af79-eaca3d2a27c0)

## Bottle and Inverted Residual Block
![Bottle_Inverted_Residual_Block](https://github.com/user-attachments/assets/d74a4292-dc96-40cd-abb7-b5e03c5a3203)

## Dual Cross General Convolution Block (DCGC Block)
![DCGC_Block](https://github.com/user-attachments/assets/2439c121-17b3-48ca-9ef6-c138b31d69a7)

## Deep Block
![Deep_Block](https://github.com/user-attachments/assets/87294240-32f1-4183-b188-9326fb15afae)

## Result
- **DCGC Deep Net** : Dice Coefficent, Jaccard Index (IoU) and Accuracy Metric
![metric](https://github.com/user-attachments/assets/9cf7b348-0193-4fee-95e8-9fe91c65e3e8)

