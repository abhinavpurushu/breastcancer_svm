# Breast Cancer Classification using Support Vector Machines (SVM)

## Overview
This project implements binary classification using Support Vector Machines (SVM) with both linear and RBF kernels. It includes hyperparameter tuning, evaluation, and decision boundary visualization using the Breast Cancer Wisconsin dataset.

# Dataset
Source: Breast Cancer Wisconsin Dataset from Kaggle

Features: 30 numerical attributes (e.g., radius, texture, perimeter, area)

Target Variable: Diagnosis (M = Malignant, B = Benign)

# Steps Covered
1. Imported necessary libraries.
2. Loaded and preprocessed the dataset (handled missing values, encoded target labels).
3. Standardized the features using StandardScaler.
4. Split the dataset into training and testing sets (80-20 split).
5. Trained SVM models with both linear and RBF kernels.
6. Tuned hyperparameters (C, gamma).
7. Evaluated model performance using classification metrics and Cross-Validation.
8. Visualized decision boundaries using two selected features.

# Results
Both SVM models achieved high accuracy, with the RBF kernel slightly outperforming the linear kernel after hyperparameter tuning. The decision boundary visualization provides insight into the model's classification regions.
