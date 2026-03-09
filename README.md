# Diabetes Prediction ML Project

This project is an end-to-end Machine Learning application that predicts whether a person is diabetic or non-diabetic based on medical attributes. The model is trained using Logistic Regression and deployed using a Flask web application.

## Project Overview

The goal of this project is to build a machine learning pipeline that:
- Preprocesses medical data
- Trains a classification model
- Saves the trained model and scaler
- Deploys the model using a Flask web application

Users can enter health parameters through a web interface and receive a prediction instantly.

## Dataset

The dataset used is the **Pima Indians Diabetes Dataset**.

Features used for prediction:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Target Variable:
- Outcome (0 = Non-Diabetic, 1 = Diabetic)

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Flask
- HTML

## Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Scaling (StandardScaler)
4. Model Training (Logistic Regression)
5. Model Evaluation
6. Model Serialization using Pickle
7. Deployment with Flask

## Project Structure
