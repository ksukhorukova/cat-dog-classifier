#Cat&Dog Classifier

Capstone project for Advanced Deep Learning for AI Applications course

## Overview

A binary image classifier that distinguishes cats from dogs using transfer learning with ResNet18, trained on the Oxford-IIIT Pet Dataset

## Results

| Metric | Value |
|--------|-------|
| Test accuracy | 80% |
| Top-1 error rate | 20.20% |
| AUC-ROC | 0.885 |

## Approach

- **Dataset:** Oxford-IIIT Pet Dataset (37 breeds - binary: cat/dog)
- **Model:** ResNet18 pretrained on ImageNet, fine-tuned on pets
- **Training:** 10 epochs, Adam optimizer with differential learning rates
- **Interface:** Gradio web app for real-time inference

## Tech Stack

- PyTorch
- torchvision
- scikit-learn
- Gradio
- matplotlib/seaborn
