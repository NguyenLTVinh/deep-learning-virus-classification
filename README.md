# Hybrid CNN-ViT Malware Classification
This project implements a hybrid deep learning model combining Convolutional Neural Networks (CNN) and Vision Transformers (ViT) to classify malware from executable images. The project also explores transfer learning with ResNet-18 and EfficientNet-B0.

## Papar
* See the paper [here](https://nguyenltvinh.github.io/assets/DeepLearningVirus.pdf)

## Features

* CNN-ViT hybrid model for malware-family classification.
* Transfer learning for malware vs. benign software classification.
* Evaluates model performance with accuracy, weighted precision, recall, and F1 score.
* Dataset: [VirusMNIST](https://arxiv.org/abs/2103.00602).

## Results

* CNN-ViT model: **91% accuracy** on malware-family classification.
* Transfer learning (ResNet-18, EfficientNet-B0): **86% accuracy** on malware vs. benign software.
* Surpasses VirusMNIST benchmark in weighted precision, recall, and F1 score.
