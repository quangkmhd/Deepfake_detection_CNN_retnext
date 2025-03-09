# Deepfake Detection Using CNN and Resnet

This project aims to detect deepfake videos by leveraging deep learning techniques, specifically using Convolutional Neural Networks (CNN) and resnet architectures. Deepfakes are synthetic media where a person's likeness is replaced with someone else's, often leading to misinformation and privacy concerns. Detecting such manipulated content is crucial in maintaining the integrity of visual media.


## Introduction

With the advancement of deep learning algorithms, creating realistic human-synthesized videos, known as deepfakes, has become increasingly accessible. These videos can be misused for malicious purposes, including disinformation campaigns and personal defamation. This project presents a deep learning-based method to distinguish between authentic and AI-generated fraudulent videos, focusing on detecting replacement and reenactment deepfakes. The core of our system utilizes a ResNeXt Convolutional Neural Network to extract frame-level features, which are then processed to identify inconsistencies indicative of deepfakes.

## System Architecture

The system architecture comprises the following components:

1. **Frame Extraction**: Videos are decomposed into individual frames to analyze temporal features.
2. **Feature Extraction**: Each frame is processed using a pre-trained ResNeXt CNN to obtain feature vectors.
3. **Classification**: The extracted features are fed into a classifier to determine the authenticity of the video.

## Requirements

To run this project, ensure you have the following software and libraries installed:

- Python 3.7 or higher
- Jupyter Notebook
- OpenCV
- PyTorch
- NumPy
- Matplotlib


## Usage

1. **Prepare the Dataset**:
2. **Extract Frames from Videos**
3. **Train the Model**
4. **Evaluate the Model**
5. **Detect Deepfakes in New Videos**

## Dataset

I use publicly available datasets for training and evaluation:

- **Celeb-DF (Version 2)**: [Download here](https://www.kaggle.com/datasets/reubensuju/celeb-df-v2)
- **Celeb-DF (Version 1)**: [Download here](https://www.kaggle.com/datasets/asifmzx/celeb-v1-df)



