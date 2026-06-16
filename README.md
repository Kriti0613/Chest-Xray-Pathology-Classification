# Chest X-Ray Pathology Classification

Deep learning project focused on classifying chest X-ray images into 20 thoracic pathology categories using transfer learning and medical image analysis techniques.

## Overview

This project develops an image classification model to identify thoracic pathologies from chest X-ray images. The workflow addresses common medical imaging challenges such as severe class imbalance, limited samples for rare diseases, and clinically important false-negative errors.

## Dataset

The dataset contains chest X-ray images annotated with 20 pathology classes, including a No Finding category.

- Training Images: 51,043
- Test Images: 17,015
- Classes: 20

**Task:** Multi-Class Image Classification

## Methodology

- Label generation from one-hot encoded pathology columns
- Stratified train-validation split
- Image preprocessing and normalization
- Data augmentation using:
  - Random Horizontal Flip
  - Random Rotation
  - Color Jitter
- Class imbalance handling through weighted loss functions
- Transfer learning with DenseNet121
- Model training and evaluation

## Model

- DenseNet121
- Pretrained feature extractor
- Custom classification head for 20 pathology classes

## Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- PIL
- Matplotlib

## Skills Demonstrated

- Medical Image Analysis
- Computer Vision
- Deep Learning
- Transfer Learning
- Multi-Class Classification
- Data Augmentation
- Class Imbalance Handling
- Model Evaluation
