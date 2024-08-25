# A Comprehensive Analysis of VGG16 and ResNet50 Models in Sign Language Recognition

## Overview

This project presents a detailed analysis and comparison of two prominent Convolutional Neural Network (CNN) architectures, VGG16 and ResNet50, in the context of Sign Language Recognition (SLR). The study aims to evaluate the performance, accuracy, and efficiency of these models in recognizing American Sign Language (ASL) alphabets and numbers.

## Table of Contents
- [Background](#background)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Models](#models)
- [Results](#results)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Background

Convolutional Neural Networks (CNNs) are a type of deep learning architecture designed specifically for processing structured grid data, such as images. They consist of multiple layers:
- **Convolutional Layers:** Apply filters to input data to extract features like edges and textures.
- **Pooling Layers:** Down-sample the data to reduce dimensionality.
- **Fully Connected Layers:** Integrate the extracted features to make predictions.

CNNs have achieved state-of-the-art performance in various tasks, including image classification and object detection, making them ideal for the task of sign language recognition.

## Objectives

The primary objectives of this project are:
1. Implement a CNN-based system trained on a dataset of ASL alphabets and numbers.
2. Evaluate the performance of the VGG16 and ResNet50 models in sign language recognition.
3. Compare the accuracy and efficiency of the VGG16 and ResNet50 models.

## Dataset

The dataset used in this project consists of images of ASL alphabets and numbers:
- **Training Data:** 300 images per alphabet and number.
- **Evaluation Data:** 100 images per alphabet and number.

The dataset is divided into training and testing sections in an 80:20 ratio.

## Models

### VGG16
VGG16 is a 16-layer CNN known for its simplicity and effectiveness. It is particularly useful for smaller datasets and scenarios where computational resources are limited.

### ResNet50
ResNet50 is a 50-layer CNN that introduces residual learning to overcome the vanishing gradient problem, allowing for deeper networks. It is ideal for more complex scenarios with larger datasets.

## Results

- **VGG16:** Demonstrated strong performance in scenarios where quick deployment and simplicity are prioritized.
- **ResNet50:** Excelled in more complex scenarios, providing higher accuracy due to deeper feature extraction.

The analysis provided insights into when to use each model based on specific needs, contributing to the development of more efficient and accurate SLR systems.

## Requirements

To run this project, you'll need the following:
- Python 3.7 or higher
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

### Clone the repository.

## Acknowledgements
This project was presented at the 5th International Conference of Emerging Technology (INCET 2024) and is based on the research paper published on the IEEE website.
Paper link: https://ieeexplore.ieee.org/document/10593346


