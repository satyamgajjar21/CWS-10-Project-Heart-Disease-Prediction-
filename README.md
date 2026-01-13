## Heart Disease Prediction Using Machine Learning

This project aims to predict the presence of heart disease in patients using supervised machine learning techniques based on medical attributes.

## Overview

Heart disease is one of the leading causes of death worldwide.
Early detection can significantly improve treatment outcomes.
This project uses patient health data to train machine learning models that can predict whether a person is likely to have heart disease.

The complete workflow includes data preprocessing, exploratory data analysis, model training, evaluation, and prediction.

## Problem Statement

To build a machine learning model that accurately predicts heart disease using clinical and demographic features such as age, cholesterol levels, blood pressure, and heart rate.

The goal is to assist in early diagnosis and decision making.

## Dataset Description

The dataset consists of patient health records containing both numerical and categorical features.

Features include age, sex, chest pain type, resting blood pressure, cholesterol level, fasting blood sugar, ECG results, maximum heart rate, exercise induced angina, and others.

Target variable  
Presence of heart disease represented as a binary outcome.

## Technologies Used

Python  
NumPy  
Pandas  
Matplotlib  
Seaborn  
Scikit learn  
Jupyter Notebook  

## Project Workflow

1. Data loading and inspection  
2. Data cleaning and preprocessing  
3. Exploratory data analysis  
4. Feature scaling and encoding  
5. Model training  
6. Model evaluation  
7. Prediction  

## Exploratory Data Analysis

Explored feature distributions to understand patient characteristics.
Analyzed correlation between health attributes and heart disease.
Visualized patterns using histograms, heatmaps, and count plots to identify key contributing factors.

## Data Preprocessing

Handled missing values where required.
Encoded categorical features into numerical format.
Applied feature scaling to normalize numerical values.
Split dataset into training and testing sets.

## Model Selection

The following machine learning models were implemented and evaluated.

Logistic Regression  
K Nearest Neighbors  
Support Vector Machine  
Decision Tree  
Random Forest  

Each model was compared based on performance metrics to determine the most effective predictor.

## Model Evaluation

Models were evaluated using accuracy score and confusion matrix.
Performance comparison helped identify the best performing model.
The final selected model demonstrated reliable prediction capability on unseen data.

## Results

The trained model successfully classified patients with and without heart disease.
Results indicate that machine learning can effectively assist in early heart disease detection when provided with quality medical data.

## How to Run This Project

1. Clone the repository  
2. Install required Python libraries  
3. Open the Heart Disease Prediction notebook  
4. Run all cells in order  

## Future Improvements

Use larger and more diverse datasets  
Apply hyperparameter tuning  
Implement cross validation  
Deploy the model using a web interface  

## Conclusion

This project demonstrates the practical application of machine learning in healthcare.
It highlights how data driven models can support medical diagnosis and improve decision making.

## Author

Satyam Gajjar
