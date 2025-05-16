# 🏠 House Prices - Kaggle ML Competition

This repository contains my solution to the [Kaggle competition: House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/home-data-for-ml-course), part of the Kaggle Learn Machine Learning course.

## 📚 Overview

The goal of this project is to predict final house sale prices based on a set of numerical and categorical features using supervised machine learning models.

I focused on:
- Data cleaning and preprocessing
- Handling missing values and outliers
- Normalization and encoding
- Model building with deep learning (Keras)
- Evaluation with MAE 
- Visualization of training and validation performance

## 🧰 Tech Stack

- Python
- Pandas / NumPy
- scikit-learn
- TensorFlow / Keras
- Matplotlib

## 🧪 Model

The final model is a feedforward neural network trained using Keras. It includes:
- Dense layers with ReLU activation
- Dropout for regularization
- EarlyStopping to avoid overfitting
- Normalized input features
- Mean Absolute Error (MAE) as the loss function

Performance is monitored using validation loss and R² score on a held-out test set.

## 📈 Results

The model shows a steady decrease in both training and validation losses, with no significant overfitting observed. Visual inspection of learning curves confirms stable learning dynamics.


