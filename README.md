# Brain Tumor Segmentation and Classification

A deep learning project for brain image segmentation and classification using a joint U-Net-based architecture with an attention mechanism.

## Overview

This project combines image segmentation and classification in a multi-task learning framework. A shared encoder extracts image features, while separate decoder and classification components perform segmentation and class prediction.

## Model

- U-Net-based encoder-decoder
- Attention-based segmentation decoder
- Classification head using encoder features
- Joint segmentation and classification training

## Workflow

- BRISC2025 dataset preparation
- Image and mask preprocessing
- Data augmentation
- Joint model training
- Model checkpointing
- Segmentation and classification evaluation
- Confusion matrix and performance metrics

## Technologies

- Python
- PyTorch
- Torchvision
- Scikit-learn
- NumPy
- Matplotlib
- Seaborn

## Dataset

This project uses the BRISC2025 brain image dataset. The dataset is not included in this repository.
