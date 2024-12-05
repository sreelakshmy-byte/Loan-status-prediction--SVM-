# Loan-status-prediction--SVM-
Loan Status Prediction System implimenting Support Vector Meshine

This project implements a Loan Status Prediction system using Support Vector Machine (SVM). The dataset is preprocessed, features are scaled, and a predictive model is trained to determine the likelihood of loan approval based on the input data.

Project Overview

The Loan Status Prediction system analyzes various attributes of loan applicants and predicts whether a loan should be approved or rejected. The system uses a machine learning approach, specifically the Support Vector Machine (SVM) algorithm, to make predictions. The project is implemented in Python.

Features of the System

Preprocessing of the dataset, including handling missing values, feature scaling, and encoding categorical variables.

Training a SVM classifier for loan status prediction.

Hyperparameter tuning for optimal model performance.

Predicting loan status for new input data.

Organized pipeline for easy reproduction of results.

Dataset

The dataset contains the following features:

Gender: Male/Female
Married: Yes/No
Dependents: Number of dependents
Education: Graduate/Not Graduate
Self_Employed: Yes/No
ApplicantIncome: Income of the applicant
CoapplicantIncome: Income of the co-applicant
LoanAmount: Loan amount requested
Loan_Amount_Term: Loan repayment term (in months)
Credit_History: Credit history record (1/0)
Property_Area: Rural/Semiurban/Urban

The target variable is Loan_Status, indicating whether a loan is approved (Y) or rejected (N).

Model Training
The model is built using the following steps:

Data Preprocessing:

Handling missing values.
Encoding categorical variables.
Scaling numerical features.
Model Selection:

Support Vector Machine (SVM) with a linear kernel is used.
Model Evaluation:

Accuracy score is used to evaluate the performance of the model on both training and testing datasets.
Prediction:

The model predicts loan status based on user input.



