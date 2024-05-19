# House Prices - Advanced Regression Techniques Competition

This repository contains my submission for the Kaggle competition "House Prices - Advanced Regression Techniques". The project aims to predict house sale prices using various features of residential homes.

## Introduction

The objective of this project is to build a regression model to predict the sale prices of houses. Using a dataset provided by Kaggle, the goal is to minimize the mean absolute error between the predicted and actual house prices.

## Dependencies

Key libraries used in this project include:
- `kaggle` for downloading the dataset.
- `numpy` and `pandas` for data manipulation.
- `matplotlib` and `seaborn` for data visualization.
- `scikit-learn` for machine learning utilities.
- `xgboost` for building the regression model.

## Data Preprocessing

### Handling Missing Values

- Numerical features were imputed using median values.
- Categorical features were filled with "MISSING" and one-hot encoded.

### Feature Engineering

- Combined numerical and one-hot encoded categorical features to prepare the dataset for modeling.

## Modeling

The primary model used was `XGBRegressor` from the `xgboost` library. Initial training was done using default parameters to establish a baseline.

### Model Improvement

- Hyperparameter tuning was conducted to improve model performance.
- Recursive Feature Elimination (RFE) was used to select important features and refine the model further.

## Final Predictions

The optimized model was used to make predictions on the test dataset, which were then saved for submission to Kaggle.

## Submission

The predictions were saved to a CSV file and submitted to the Kaggle competition.

## Rank

The final rank achieved in the competition was 2256.

This project demonstrates a structured approach to handling a regression problem with a focus on data preprocessing, feature engineering, and model optimization.
