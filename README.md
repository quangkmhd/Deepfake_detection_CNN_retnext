# Deepfake Detection Using CNN and Resnet

This project aims to detect deepfake videos by leveraging deep learning techniques, specifically using Convolutional Neural Networks (CNN) and resnet architectures. Deepfakes are synthetic media where a person's likeness is replaced with someone else's, often leading to misinformation and privacy concerns. Detecting such manipulated content is crucial in maintaining the integrity of visual media.


## Introduction

This project aims to detect deepfake videos by extracting faces from real and fake videos, preprocessing them, and training a deep learning model based on ResNet50 to distinguish between real and fake faces. The dataset includes videos from Celeb-DF v1 and v2 datasets. The workflow involves:

Extracting frames from videos

Detecting faces and contextual regions

Preprocessing and splitting data

Training a CNN classifier

## ✨ Features
Frame extraction from video at custom intervals

Face detection using Haar cascades

Contextual region extraction

Balanced dataset splitting

Model training using pretrained ResNet50

Real-time training accuracy and loss reporting



## Requirements

To run this project, ensure you have the following software and libraries installed:

- Python 

- NumPy

- Pandas

- OpenCV

- PyTorch

- Torchvision


##👨‍💻 Contributors
Nguyễn Hữu Quang – Initial Work




## Dataset

I use publicly available datasets for training and evaluation:

- **Celeb-DF (Version 2)**: [Download here](https://www.kaggle.com/datasets/reubensuju/celeb-df-v2)
- **Celeb-DF (Version 1)**: [Download here](https://www.kaggle.com/datasets/asifmzx/celeb-v1-df)



