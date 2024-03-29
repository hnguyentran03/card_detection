# Changelog

All notable changes to this project will be documented in this file.

## Jan-11-2024

## ADDED

- Feature engineering of gender and age after analysis of SHAP values

## CHANGED

- Fixed plots to be smaller and more viewable
- Changed the pie plot comparing the imbalance in train, test and validation sets to just be percentages

## Jan-10-2024

### ADDED

- AdaBoost
- Beeswarm plot to analyze SHAP values
- Summary

### REMOVED

- Decision Tree
- Random Forest
- Logistic Regression

### CHANGED

- Train test splits are now done by time instead of train_test_split()
- Hyperparameter tuning changed from RandomSearchCV to Optuna
- Moved final testing to be below SHAP calculations

## Jan-9-2024

### ADDED

- Calculation of SHAP values
- Exploratory Data Analysis

## Jan-8-2024

### ADDED

- Added a cross validation set and testing

### CHANGED

- Replaced GridSearchCV with RandomSearchCV

## Jan-5-2024

### ADDED

- Logistic Regression and Random Forest as baseline performance

### FIXED

- Fixed the data preprocessing to address data leakaged
- Removed private information from training and testing data
- Feature engineering to create features like age and time of day
- Normalized data

## Jan-4-2024

### ADDED

- XGBoost
- Hyperparameter tuning using GridSearchCV

### CHANGED

- Changed from using One Hot Encodings to Ordinal Encodings

### REMOVED

- Unused fraudTest.csv data set

## Jan-3-2024

### ADDED

- Transferred code to a Jupyter Notebook
- Plot to show imbalance in data
- SMOTE + Tomek Links
- One Hot Encodings for categorical data

### REMOVED

- Main Python file

## Jan-2-2024

## ADDED

- Main Python file
- fraudTrain.csv and fraudTest.csv for the data sets
- Preliminary data preprocessing
- Decision Tree and Random Forest Algorithm
- Manual hyperparemter tuning via plots