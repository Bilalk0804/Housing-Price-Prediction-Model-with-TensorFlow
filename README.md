# PRODIGY_ML_1
# Housing Price Prediction using TensorFlow

This repository contains a housing price prediction model built using TensorFlow. The model is designed to predict the prices of houses based on various features such as location, size, and other relevant attributes. This project was developed and trained using data from Kaggle.

## Overview

The goal of this project is to create a machine learning model that accurately predicts housing prices. This can be useful for real estate companies, buyers, and sellers to understand market trends and make informed decisions.

## Dataset

The dataset used for training and testing the model is sourced from Kaggle. It includes various features such as:

- Location
- Number of bedrooms
- Number of bathrooms
- Square footage
- Year built
- Lot size
- And other relevant features

## Model

The model is built using TensorFlow and includes the following steps:

1. **Data Preprocessing**:
    - Handling missing values
    - Feature scaling
    - Encoding categorical variables

2. **Model Architecture**:
    - The model is a feedforward neural network with multiple layers:
        - Input layer corresponding to the number of features
        - Hidden layers with ReLU activation functions
        - Output layer with a single node to predict the price

3. **Training**:
    - The model is trained using the mean squared error (MSE) as the loss function.
    - The Adam optimizer is used for training the model.

4. **Evaluation**:
    - The model's performance is evaluated on a test set, and metrics such as MSE and R^2 are reported.

