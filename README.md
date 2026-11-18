# CNN for Image Classification using CIFAR-10

A Convolutional Neural Network (CNN) built using PyTorch to classify images from the CIFAR-10 dataset into 10 categories.

## Project Overview

This project demonstrates image classification using deep learning and a custom CNN architecture implemented with PyTorch.

## Technologies Used

- Python
- PyTorch
- Torchvision
- Jupyter Notebook
- CIFAR-10 Dataset

## Model Architecture

The CNN consists of:

- 3 convolutional layers
- ReLU activation functions
- 3 max-pooling layers
- Fully connected layer with 256 neurons
- Output layer with 10 classes

## Training Configuration

| Parameter | Value |
|---|---|
| Dataset | CIFAR-10 |
| Batch Size | 64 |
| Epochs | 10 |
| Optimizer | Adam |
| Loss Function | Cross Entropy Loss |
| Image Normalization | Mean 0.5, Std 0.5 |

## Project Structure

```text
CNN for Image Classification/
│
├── CNN_for_CIFAR10.ipynb
├── requirements.txt
├── README.md
└── .gitignore
