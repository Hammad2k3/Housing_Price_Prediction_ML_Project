
# House Price Prediction

## Overview
This repository contains code for predicting house prices using machine learning techniques. The code involves data exploration, preprocessing, model training, and evaluation. It uses the popular Python libraries such as Pandas, Matplotlib, Seaborn, and Scikit-Learn. It uses SVM, Random Forest Regression & Linear Regression algorithms and then MAPE for each algorithm is calculated to find most suitable algorithm for our dataset

## Importing required libraries & dataset
For this project first we import required libraries such as Pandas, Matplotlib, Seaborn, & Scikit-learn. Using Pandas built-in read_excel function, we will import our dataset which is in .xlsx format.

## About Dataset
Our data set consists of 13 features and 98 rows. Out of 13 features; 6 have integer values, 3 have float values and 4 have categorical values

## Data Preprocessing:
Following steps were performed on our dataset:

- Performing EDA, including using Heatmap for finding correlation as well as analyzing different features
- Handling missing values, including dropping unnecessary columns and imputing missing values in the target variable.
- Using one-hot encoding to handle categorical features.

## Model Training:
Training dataset with following three regression models after splitting dataset into training and testing:
 - Support Vector Regression (SVR)
 - Random Forest Regression (RFR)
 - Linear Regression (LR).

## Model Evaluation:

Using Mean Absolute Percentage Error (MAPE) for evaluating each model performance.


## Visualizations used:

- Heatmap for correlation analysis.
- Bar plots for unique values and distribution of categorical features.

- ## Conclusion

- -According to calculated MAPE Value for each algorithm, SVM has better accuracy compared to the other two algorithms so it is more suitable for our dataset.
