# CT Scan-Based COVID-19 Detection using Feature Extraction and Ensemble Models

This project focuses on detecting COVID-19 from lung CT scan images using deep learning for feature extraction and stacking ensemble methods (XGBoost, LightGBM, SVM, ANN) for classification.

##Dataset

- **Source:** [SARS-CoV-2 CT-Scan Dataset](https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset)
- Categories: COVID / Non-COVID
- Total images: 2481

> Due to GitHub file size limits, please download the dataset manually from the link above.

## Problem Statement

To build an intelligent system that automatically detects COVID-19 using CT scans and machine learning algorithms with a focus on improving accuracy and reducing false positives.

## Methodology

1. **Data Preprocessing**
   - Image resizing, grayscale conversion
   - Denoising and normalization
2. **Feature Extraction**
   - InceptionV3, ResNet50
3. **Modeling**
   - Base models: XGBoost, LightGBM, SVM
   - Meta-learner: ANN
   - Ensemble via stacking
4. **Evaluation**
   - Accuracy, precision, recall, F1-score, confusion matrix



