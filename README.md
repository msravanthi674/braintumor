# Brain Tumor Classification using MLP

This project implements a Multi-Layer Perceptron (MLP) neural network to classify brain tumor MRI images into four categories: pituitary, no tumor, meningioma, and glioma.

## Overview
The model processes brain MRI images of size 224x224x3 and classifies them into four distinct categories. Using a simple MLP architecture, it achieves approximately 82% validation accuracy.

## Dataset
The dataset contains brain MRI images split into training and testing sets, with four classes:
- Pituitary tumor
- No tumor
- Meningioma
- Glioma

## Model Architecture
- Input Layer: 224x224x3 (flattened)
- Hidden Layers:
  - Dense layer (92 units, ReLU)
  - Dense layer (64 units, ReLU)
  - Dense layer (32 units, ReLU)
- Output Layer: 4 units (Softmax)

## Performance
- Training Accuracy: ~100%
- Validation Accuracy: ~82%
- Training Time: 20 epochs

The model includes visualization capabilities for both sample images and training metrics.
