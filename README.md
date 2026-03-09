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

The dataset used is the Pima Indians Diabetes Dataset.

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

Outcome  
0 = Non-Diabetic  
1 = Diabetic

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Flask
- HTML
- Pickle

## Machine Learning Workflow

1 Data Collection  
2 Data Preprocessing  
3 Feature Scaling using StandardScaler  
4 Model Training using Logistic Regression  
5 Model Evaluation  
6 Model Serialization using Pickle  
7 Deployment with Flask

## Project Structure
```
diabetes-prediction-ml-flask-app
│
├── Model
│   ├── modelForPrediction.pkl
│   └── StandardScaler.pkl
│
├── dataset
│   └── diabetes.csv
│
├── Notebook
│   └── Logistic_Regression_Diabetes.ipynb
│
├── templates
│   ├── home.html
│   └── single_prediction.html
│
├── app.py
├── requirements.txt
└── README.md
```

## Running the Project Locally

Clone the repository

git clone https://github.com/PriyankaMittha/diabetes-prediction-ml-flask-app.git

Navigate to project folder

cd diabetes-prediction-ml-flask-app

Install dependencies

pip install -r requirements.txt

Run the Flask application

python app.py

Open browser and go to

http://127.0.0.1:5000

## Web Application

The web interface allows users to input medical details and get a prediction whether the person is diabetic or not.

## Future Improvements

- Add more advanced ML models
- Improve UI design
- Add model monitoring
- Deploy using cloud platforms
- Convert the project into a full ML pipeline

## Author

Priyanka Mittha

GitHub  
https://github.com/PriyankaMittha

LinkedIn  
https://www.linkedin.com/in/priyanka-mittha
