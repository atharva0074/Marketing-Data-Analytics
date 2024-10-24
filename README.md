# Marketing-Data-Analytics

## Overview

This project focuses on analyzing a dataset containing customer demographic information to predict customer loyalty and purchase behavior using logistic regression.

## Dataset

The dataset used in this project is `a1_Dataset_10Percent.xlsx`, which includes various demographic features and a target variable indicating customer purchasing behavior.

## Requirements

Ensure you have the following Python packages installed:

- numpy
- pandas
- scikit-learn
- openpyxl (for reading Excel files)

You can install these packages via pip:

```bash
pip install numpy pandas scikit-learn openpyxl


## Project Structure

├── a1_Dataset_10Percent.xlsx  # The dataset file
├── marketing_analytics.py      # The main Python script
└── README.md                   # Project documentation


 ## Steps:
Load the Data: The dataset is loaded into a Pandas DataFrame.

## Data Preprocessing:
Analyze and fill missing values with the mode (for categorical variables) or mean (for numerical variables).
Convert categorical variables into numerical format using label encoding.

## Exploratory Data Analysis:
Check unique values and counts of customers in each loyalty class.

## Model Training:
Split the data into training and testing sets.
Train a Logistic Regression model using the training data.

## Model Evaluation:
Predict outcomes on the test set and evaluate model performance using a confusion matrix and accuracy score.

## Results:
After execution, the confusion matrix and accuracy score will be displayed in the console, providing insights into the model's performance.
