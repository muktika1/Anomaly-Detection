# Anomaly-Detection-using-Multi-Perceptron

## Overview
This project implements an online fraud detection system using machine learning techniques. The goal is to identify fraudulent transactions from a dataset of online transactions. Several models are built and evaluated, including a basic neural network, an MLP model with regularization, and a BaggingClassifier with a Keras base model.

## Features

Data Visualization
The project includes various visualizations:

Distribution of transaction steps
Distribution of fraudulent vs non-fraudulent transactions
Transaction type counts for fraudulent and non-fraudulent transactions
Correlation heatmap of numerical features

Model Details
Basic Neural Network:

Architecture: Dense layers with ReLU activation and dropout for regularization.
Performance: Accuracy of 91%, precision of 88%, recall of 94%, F1-score of 91%.
MLP with Regularization:

Architecture: Dense layers with L1 and L2 regularization.
Performance: Accuracy of 81%, precision of 86%, recall of 73%, F1-score of 79%.
Bagging Classifier:

Architecture: Ensemble of Keras models using Bagging.
Performance: Accuracy of 89%, precision of 98%, recall of 79%, F1-score of 87%.

Results
The Bagging Classifier model performed the best, achieving high precision and overall accuracy.
