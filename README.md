# README

## Overview
This project focuses on building and evaluating machine learning models to predict customer churn using the Telco Customer Churn dataset. The dataset contains various features related to customer demographics, account information, and services.

## Data Preparation
1. **Load Dataset**: Read the Telco Customer Churn dataset.
2. **Data Cleaning**: Handle missing values and ensure correct data types.
3. **Feature Engineering**: Create new features based on existing data.

## Exploratory Data Analysis (EDA)
- **Numerical Features**: Summarize and visualize the distribution of numerical features.
- **Categorical Features**: Summarize and visualize the distribution of categorical features.
- **Correlation Analysis**: Analyze correlations between numerical features.

## Handling Missing Values
Fill missing values in the `TotalCharges` column with the median.

## Encoding and Scaling
- **Label Encoding**: Apply label encoding to binary categorical variables.
- **One-Hot Encoding**: Apply one-hot encoding to other categorical variables.
- **Scaling**: Standardize numerical features.

## Handling Data Imbalance
Use SMOTE to handle class imbalance in the target variable.

## Model Building and Evaluation
- Split the data into training and testing sets.
- Train and evaluate various machine learning models:
  - Logistic Regression
  - K-Nearest Neighbors
  - Decision Tree Classifier
  - Random Forest Classifier
  - Support Vector Machine
  - XGBoost
  - LightGBM
  - CatBoost

Evaluate models using accuracy, precision, recall, F1 score, and ROC AUC score.

## Hyperparameter Optimization
Use GridSearchCV for hyperparameter tuning of the best-performing models.

## Ensemble Learning
Build a Voting Classifier using the best models from hyperparameter tuning.

## Feature Importance
Plot feature importances for the best models.

## ROC Curve
Generate and plot the ROC curve for the best models.

