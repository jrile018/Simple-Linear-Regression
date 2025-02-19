# Simple-Linear-Regression

Overview

This project demonstrates simple linear regression using Python and the Scikit-Learn library. The model is trained to predict salaries based on years of experience.

Prerequisites

Ensure you have the following dependencies installed:

Python 3.x

NumPy

Matplotlib

Pandas

Scikit-Learn

You can install the required packages using:

pip install numpy matplotlib pandas scikit-learn

Dataset

The dataset (Data.csv) should contain two columns:

YearsExperience - The number of years of experience.

Salary - The corresponding salary.

Code Breakdown

Import Libraries

numpy, matplotlib.pyplot, and pandas for data handling and visualization.

sklearn.model_selection.train_test_split for splitting the dataset.

sklearn.linear_model.LinearRegression for implementing the regression model.

Load Dataset

Reads the Data.csv file into a Pandas DataFrame.

Splits the dataset into independent variables (X) and dependent variables (y).

Train-Test Split

Splits the data into a training set (2/3) and a test set (1/3).

Train the Model

Uses LinearRegression() to fit the model with training data.

Make Predictions

Predicts salary values for the test set.

Visualization

Plots training set results with a regression line.

Plots test set results with the same regression line.

Running the Code

Ensure Data.csv is in the working directory.

Run the script:

python script.py

The plots for training and test sets will be displayed.

Expected Output

Two scatter plots:

Training Set: Displays the data points and regression line.

Test Set: Shows test data and the regression line obtained from training data.

Notes

The dataset should not contain missing values.

The random_state=0 ensures reproducibility.
