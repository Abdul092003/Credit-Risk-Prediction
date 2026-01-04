# Credit Risk Prediction 
## Overview

Credit risk prediction is a crucial task in the banking and financial sector. This project focuses on building a machine learning model to predict whether a loan applicant is likely to default or not default based on historical loan data and applicant information.

The goal is to help financial institutions make data-driven lending decisions and minimize financial risk.

# Problem Statement

Loan defaults can lead to significant losses for banks. By analyzing customer attributes such as income, education, loan amount, and credit history, we can predict the creditworthiness of applicants.

This project uses supervised machine learning to classify applicants into:

Defaulter

Non-Defaulter

Dataset

The dataset contains historical loan application data with features such as:

Applicant Income

Co-applicant Income

Loan Amount

Loan Term

Credit History

Education

Gender

Marital Status

(Target variable indicates loan approval / default behavior.)

Technologies Used

Python

Jupyter Notebook

Pandas & NumPy – Data manipulation

Matplotlib & Seaborn – Data visualization

Scikit-learn – Machine learning models & evaluation

# Project Workflow

Importing Libraries

Loading the Dataset

Exploratory Data Analysis (EDA)

Data Cleaning & Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling

Model Building

Logistic Regression

Model Evaluation

Accuracy Score

Confusion Matrix

Heatmap Visualization

Machine Learning Model

# Algorithm Used: Logistic Regression

## Reason:

Simple and effective for binary classification

Easy to interpret

Performs well on structured financial data

Model Performance

The model is evaluated using:

Accuracy Score

Confusion Matrix

Heatmap Visualization

These metrics help assess how well the model distinguishes between defaulters and non-defaulters.

# Results

The Logistic Regression model successfully predicts credit risk with good accuracy, making it suitable as a baseline model for loan default prediction.
