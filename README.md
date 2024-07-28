# MNIST Digit Classification Using PyTorch

## Overview
This repository implements a simple neural network to classify handwritten digits from the MNIST dataset using PyTorch. The model is trained to recognize digits from 0 to 9 based on pixel values.

## Table of Contents
- [Introduction](#introduction)
- [Data Description](#data-description)
- [Techniques Used](#techniques-used)
- [Confusion Matrix](#confusion-matrix)
- [Conclusion](#conclusion)

## Introduction
The MNIST dataset is a well-known dataset for training image processing systems. This project uses a simple feedforward neural network to classify the digits based on their pixel values.

## Data Description
The MNIST dataset consists of 70,000 images of handwritten digits, each 28x28 pixels in size. The dataset is split into 60,000 training images and 10,000 test images.

## Techniques Used
- **PyTorch**: A popular deep learning framework used for building and training neural networks.
- **Feedforward Neural Network**: A simple architecture consisting of an input layer, hidden layer(s), and an output layer.

## Confusion Matrix
A confusion matrix is plotted to visualize the model's performance across different classes.

## Conclusion
The simple neural network achieves a high accuracy on the MNIST test set, demonstrating the effectiveness of neural networks for image classification tasks.
