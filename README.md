# CIFAR-100 Image Classification with ResNet-18

This repository contains a PyTorch implementation for training and evaluating a ResNet-18 model on the CIFAR-100 dataset.
The notebook demonstrates how to modify a pretrained ResNet-18 for small image sizes, apply data preprocessing, and train the model for multi-class image classification.

## Requirements
Make sure you have the following installed:

> pip install torch torchvision

Recommended environment:
- Python 3.8+
- PyTorch >= 1.12
- torchvision >= 0.13
- CUDA-capable GPU (optional)


The CIFAR-100 dataset will be automatically downloaded when `download=True` is set in the notebook’s dataset loading cell.
