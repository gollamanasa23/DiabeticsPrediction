
# Diabetes Prediction Using Machine Learning

This project leverages machine learning models to predict the likelihood of diabetes in individuals based on various medical and demographic features. The workflow involves data preprocessing, exploratory data analysis (EDA), feature scaling, model training, evaluation, and visualization.

## Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Models](#models)
6. [Performance Metrics](#performance-metrics)

---

## Overview

This project focuses on predicting diabetes using machine learning techniques. It includes exploratory data analysis to understand data distribution, data preprocessing for cleaning and transformation, and model training to achieve high prediction accuracy.

---

## Dataset

The dataset, `diabetes_prediction_dataset.csv`, contains the following features:

- **age**: Age of the individual
- **gender**: Gender of the individual (Male/Female)
- **bmi**: Body Mass Index
- **hypertension**: Presence of hypertension (0 = No, 1 = Yes)
- **heart_disease**: Presence of heart disease (0 = No, 1 = Yes)
- **smoking_history**: Smoking history (categorical)
- **diabetes**: Target variable (0 = No Diabetes, 1 = Diabetes)

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction
   cd diabetes-prediction
   ```

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Place the dataset (`diabetes_prediction_dataset.csv`) in the project directory.

---

## Usage

Run the Python script in juoyter notebook:
```bash
FinalisedCode_05-12-2024.py
```

The script will:

- Load and preprocess the dataset.
- Perform exploratory data analysis and visualize distributions.
- Train multiple machine learning models.
- Evaluate model performance using metrics and visualizations.

---

## Models

The following machine learning models are implemented:

1. Random Forest Classifier
2. Decision Tree Classifier
3. Logistic Regression
4. Gradient Boosting Classifier

Each model is trained, evaluated, and compared using cross-validation and test set metrics.

---

## Performance Metrics

The performance of models is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Area Under the ROC Curve (AUC)

Confusion matrices and ROC curves are generated for visualization.






