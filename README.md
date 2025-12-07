# SME-RFT-Predictor
SME Loan Pre-Screen: Predict Right-First-Time Applications using Logistic Regression.

# Description
This project implements a machine learning system in Google Colab to predict whether a Small and Medium Enterprise (SME) loan application is Right-First-Time (RFT), i.e., complete and eligible with all required documents submitted.
It uses Logistic Regression and provides both prediction and probability for new loan applications. A simple interactive interface using ipywidgets is included for entering new applicant data.

# Features
-> Predict RFT (Yes/No) for SME loan applications
-> Probability score for each prediction
-> Handles categorical features (Industry, Applicant Category) and Yes/No document fields
-> Interactive interface using ipywidgets
-> Preprocessing includes:
    * Yes/No → 1/0 conversion
    * One-hot encoding of categorical features
    * Handling missing columns in new applications

# Pre-requisites
  * pandas
  * scikit-learn
  * ipywidgets (for Colab dashboard)

# Mounting Google Drive
from google.colab import drive
drive.mount('/content/drive')

# Interactive Dashboard (Colab)
Use the provided ipywidgets interface to input new applicant info and get predictions in real-time.

# License
This project is licensed under the MIT License
