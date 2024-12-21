# Computer Vision Toolkit
Author: Ziad Tamim

Date: 06/10/2023


## Overview
This repository is a comprehensive computer vision toolkit developed for solving real-world problems using fundamental image and video processing techniques. The repository contains modular, reusable code for tasks such as image transformations, convolution, video segmentation, texture classification, and object counting.

The repository is structured for easy integration with datasets and real-world projects.


## Features
### 1. Image Transformations
Implements rotation, translation, and skewing operations.
Provides mathematical formulations for rotation and skewing matrices.
Allows experimentation with different angles and orders of operations for rotation and skewing.
### 2. Convolution
Custom convolution function to apply kernels of any size.
Demonstrates the use of different filters (e.g., smoothing, edge detection).
Includes experiments with kernel compositions to analyze combined effects.
### 3. Video Segmentation
Frame-based histogram computation for color analysis.
Histogram intersection function for comparing consecutive frames.
Visualization of intersections to detect scene changes and their robustness to variations.
### 4. Texture Classification
Implements Local Binary Pattern (LBP) for texture analysis.
Divides images into non-overlapping windows for local texture description.
Combines local texture features into global descriptors for classification tasks.
Includes a classification pipeline to separate face and non-face images using LBP-based descriptors.
### 5. Object Counting
Frame differencing using both the first frame and consecutive frames as references.
Background generation using temporal averaging.
Object counting using morphological operations and connected components.
Visualizes object counts per frame in a bar plot.


## Prerequisites
### Libraries
This project uses the following Python libraries:

`numpy`

`opencv-python`

`matplotlib`

`scipy`

`scikit-image`

Install them using:

`pip install -r requirements.txt`

### Dataset Structure
Ensure the dataset is organized as follows:
```
Dataset/
├── DatasetA/
│   ├── face-1.jpg
│   ├── face-2.jpg
│   ├── face-3.jpg
│   ├── car-1.jpg
│   ├── car-2.jpg
│   ├── car-3.jpg
│   └── Name in Arial.png
├── DatasetB.avi
└── DatasetC.avi

```

## Results
- Image Transformations: Analyze the effects of different transformation operations and their order.
- Convolution: Visualize the effects of applying various kernels to images.
- Video Segmentation: Detect scene changes using histogram comparisons.
- exture Classification: Classify images into face and non-face categories using LBP descriptors.
- Object Counting: Generate real-time object counts in video sequences.
