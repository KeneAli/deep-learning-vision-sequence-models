# Deep Learning for Image Classification and Human Activity Recognition

This repository contains two deep learning projects exploring neural network architectures for computer vision and time-series classification tasks.
The work compares different neural network models including MLPs, CNNs, LSTMs, GRUs, and attention-based architectures, with a focus on performance, interpretability, and architectural design.

## 1. Flickr Image Classification

This project investigates image classification using deep learning architectures.

### The objective is to classify images into five categories:

- Animals
- Objects
- People
- Scenes
- Others

## Models implemented:

- Multilayer Perceptron (MLP)
- Convolutional Neural Network (CNN)
- Transfer Learning

## Key techniques applied:

- Data preprocessing and augmentation

- Regularization and architecture tuning

- Model interpretability using Grad-CAM

## Results:

CNN models significantly outperformed MLPs and transfer learning approaches on the dataset, achieving a validation accuracy of 62.3%.

Grad-CAM was used to visualize model attention and understand learned features.

# 2. Human Activity Recognition (HAR)

This project explores sequence modeling techniques for recognizing human activities using smartphone sensor data.

### Activities classified include:

- Walking
- Sitting
- Standing
- Lying
- Walking upstairs/downstairs

## Models implemented:

- LSTM networks
- GRU networks
- Convolutional Neural Networks
- LSTM with attention mechanism

# Results:

- Both Complex CNN and LSTM with attention achieved high performance, with classification accuracies around 91.5%.

- LSTM-based models provided better interpretability, while CNNs offered faster training times.
