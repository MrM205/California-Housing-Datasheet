# Artificial Intelligence & Machine Learning – Task 3

## Model Validation, Overfitting Control & Hyperparameter Tuning

### 📌 Project Overview

This project focuses on validating machine learning models, detecting and controlling overfitting, and improving model performance through hyperparameter tuning.

The **California Housing Dataset** is used for the implementation. The project compares different regression models and evaluates their performance using **RMSE** and **R² Score**.

---

## 🎯 Objectives

The main objectives of this task are:

- Understand model validation techniques.
- Detect overfitting in Decision Tree models.
- Apply 5-Fold Cross-Validation.
- Perform hyperparameter tuning using `GridSearchCV`.
- Control Decision Tree overfitting using hyperparameters.
- Evaluate models using RMSE and R² Score.
- Compare Linear Regression, Ridge Regression, and Tuned Decision Tree.
- Select the final model based on performance and generalization.

---

## 📊 Dataset

The project uses the **California Housing Dataset**.

The dataset contains information about California housing areas and their corresponding house values.

### Target Variable

`HousePrice`

### Main Features

- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🔄 Project Workflow

```text
Load California Housing Dataset
            ↓
Data Preparation
            ↓
Feature Scaling
            ↓
Train-Test Split
            ↓
Decision Tree Baseline
            ↓
Overfitting Detection
            ↓
5-Fold Cross-Validation
            ↓
GridSearchCV
            ↓
Hyperparameter Tuning
            ↓
Optimized Decision Tree
            ↓
RMSE & R² Evaluation
            ↓
Model Comparison
            ↓
Final Model Selection
