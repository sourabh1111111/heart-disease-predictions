# heart-disease-predictions
This project is a basic machine learning project that predicts whether an individual is at risk of heart disease or not. It utilizes a dataset containing patient information such as age, cholesterol levels, and other medical indicators. The model is trained using logistic regression to classify individuals as either at risk (target = 1) or not at risk (target = 0) of heart disease.
# Features
Data Loading and Preprocessing: Load and preprocess the heart disease dataset.
Model Training: Train a Logistic Regression model to classify individuals based on their medical features.
Prediction: Predict whether a new individual is at risk of heart disease.
Evaluation: Evaluate the model's performance using various metrics.
# Example Input Data
The following are examples of input data used to train and test the model:
# Example 1 (Healthy)
age: 52, sex: 1, cp: 0, trestbps: 125, chol: 212, fbs: 0, restecg: 1, thalach: 168, exang: 0, oldpeak: 1, slope: 2, ca: 2, thal: 3, target: 0
# Example 2 (At Risk)
age: 58, sex: 0, cp: 0, trestbps: 100, chol: 248, fbs: 0, restecg: 0, thalach: 122, exang: 0, oldpeak: 1, slope: 1, ca: 0, thal: 2, target: 1
# note
In these examples, target = 1 indicates the individual is at risk of heart disease (unhealthy), and target = 0 indicates the individual is not at risk (healthy). Note that the target column is not used as an input feature for predictions; it is the label that the model predicts.

