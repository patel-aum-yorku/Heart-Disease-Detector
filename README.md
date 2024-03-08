# Heart Disease Prediction with Machine Learning

This repository contains a Jupyter notebook that explores the development of a machine learning model to predict whether an individual has heart disease based on their medical attributes. We leverage various Python-based machine learning and data science libraries to analyze, model, and evaluate the prediction accuracy.

## Table of Contents

1. [Problem Definition](#1-problem-definition)
2. [Data](#2-data)
3. [Evaluation](#3-evaluation)
4. [Features](#4-features)
5. [Modelling](#5-modelling)
    - [Model Comparison](#model-comparison)
    - [Hyperparameter Tuning](#hyperparameter-tuning)
    - [Feature Importance](#feature-importance)
6. [Experimentation](#6-experimentation)

## 1. Problem Definition

Can we predict whether or not a patient has heart disease based on clinical parameters?

## 2. Data

The dataset used for this project originates from the Cleavland data from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease). An alternative version is available on [Kaggle](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset).

## 3. Evaluation

Our goal is to achieve 95% accuracy in predicting the presence of heart disease during the proof of concept.

## 4. Features

The dataset includes various features:

- **age**: Age in years
- **sex**: (1 = male; 0 = female)
- **cp**: Chest pain type
- **trestbps**: Resting blood pressure (mm Hg on admission)
- **chol**: Serum cholesterol (mg/dl)
- **fbs**: Fasting blood sugar (> 120 mg/dl)
- **restecg**: Resting electrocardiographic results
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes; 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment
- **ca**: Number of major vessels (0-3) colored by fluoroscopy
- **thal**: Thalium stress result
- **target**: Presence of heart disease (1=yes, 0=no)

## 5. Modelling

### Model Comparison

We start with a baseline model and explore:

- Hyperparameter tuning
- Feature importance
- Confusion matrix
- Cross-validation
- Precision, Recall, F1 score
- Classification report
- ROC curve and AUC score

### Hyperparameter Tuning

Tuning Logistic Regression and Random Forest Classifier using RandomizedSearchCV.

### Feature Importance

Explore feature importance for Logistic Regression model.

## 6. Experimentation

If the evaluation metric is not met, consider:

- Collecting more data
- Trying other models (e.g., CatBoost or XGBoost)
- Improving current models beyond the current state

If the model is satisfactory, contemplate exporting and sharing it with others.


