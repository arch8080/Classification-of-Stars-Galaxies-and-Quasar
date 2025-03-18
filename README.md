# Classification-of-Stars-Galaxies-and-Quasar
Project Overview

This project utilizes multiple machine learning models to classify celestial objects based on the Stellar Classification Dataset (SDSS17). The goal is to compare different models, optimize hyperparameters using Optuna, and apply model stacking for improved classification accuracy.

# Dataset
Source: Sloan Digital Sky Survey (SDSS17)

# Features Used:
Numerical: Right Ascension (alpha), Declination (delta), Redshift, Magnitude (u, r)
Target: Object Class (Star, Galaxy, Quasar)

# Machine Learning Models Implemented
Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
k-Nearest Neighbors (k-NN)
XGBoost
LightGBM
Model Stacking:
Combines predictions from multiple models to improve performance.
Optuna Hyperparameter Optimization:
Optimizes XGBoost for better performance.

# Performance Comparison
Logistic Regression
94.71%

Decision Tree
96.04%

Random Forest
97.62%

SVM
95.57%

k-NN
94.24%

XGBoost
97.31%

LightGBM
97.60%

Stacking Model
97.63%

XGBoost Optimized
97.35%
