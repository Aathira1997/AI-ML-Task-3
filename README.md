## AI-ML-Task-3
## Linear Regression
## Overview
This project demonstrates the implementation of linear regression using a housing dataset. The objective is to understand the relationship between features and the target variable (house price), evaluate model performance and interpret model coefficients.

## Dataset
The dataset used for this project contains information about houses, including features such as area, number of bedrooms, bathrooms, parking, and more.

## Tools and Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

## Steps
1. Import and Preprocess the Dataset
Load the dataset using Pandas.
Explore the data: check for missing values, data types, and basic statistics.
Handle categorical variables using one-hot encoding with drop_first=True to avoid multicollinearity.

2. Split the Dataset
Divide the data into training and testing sets using the train_test_split() function.

3. Train Linear Regression Model
Fit a LinearRegression model using Scikit-learn on training data.
Extract and display feature coefficients to interpret the influence of each feature.

4. Evaluate the Model
Use MAE, MSE, and R² score to evaluate model accuracy.
Check for multicollinearity using Variance Inflation Factor (VIF).

5. Plot the Regression Line
Plot actual vs predicted values for visual evaluation of regression performance.

## Output
Printed model evaluation metrics: MAE, MSE, R² Score.
Feature importance via coefficients.
Regression plot: Actual vs Predicted values.










Ask ChatGPT
