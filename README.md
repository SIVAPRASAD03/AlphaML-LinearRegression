# AlphaML-LinearRegression
Quiz6

This is an implementation of a linear regressor on the California Housing from sklearn.datasets import fetch_california_housing

The code does the following:

Import Libraries: We import necessary libraries from scikit-learn for data loading, train-test split, linear regression model creation, and evaluation metrics.
Load Data: The fetch_california_housing function is used to load the California Housing dataset.
Split Data: We split the data into features (X) and target variable (y) using data attributes provided by the dataset. Then, we split the data further into training and testing sets using train_test_split for model training and evaluation.
Create Model: A linear regression model is created using the LinearRegression class.
Train Model: The model is trained on the training data using the fit method.
Make Predictions: The trained model uses the predict method to predict target values for the testing data.
Evaluate Model: The performance of the model is evaluated using mean squared error (MSE) and R-squared score (R2) calculated on the testing data.

