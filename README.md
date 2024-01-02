## Overview
This repository contains code and documentation for a logistic regression model designed to classify patients as either diabetic or non-diabetic based on specific input variables. The aim is to provide healthcare professionals and data scientists with a tool that can assist in early diagnosis and risk assessment for diabetes.

## Features
Pregnancies - Number of times pregnant

Glucose - Plasma glucose concentration in an oral glucose tolerance test

BloodPressure - Diastolic blood pressure (mm Hg)

SkinThickness - Triceps skinfold thickness (mm)

Insulin - Two hour serum insulin

BMI - Body Mass Index

DiabetesPedigreeFunction - Diabetes pedigree function

Age - Age in years

Target Variable
Outcome Class variable (either 0 or 1)
0 - No diabetes
1 - Diabetes
Outcome: Binary variable indicating diabetes status (1: diabetic, 0: non-diabetic)

## Model Training
The logistic regression model is trained using a labeled dataset containing historical patient data. The dataset is split into training and test sets to evaluate the model's performance accurately. The model is trained using the LogisticRegression algorithm from the scikit-learn library.

## Model Evaluation
Performance Metrics
The model's performance is evaluated using the following metrics:

Accuracy Score: Measures the overall correctness of the model's predictions.
Recall Score: Measures the model's ability to correctly identify diabetic patients.
Precision Score: Measures the model's accuracy in predicting diabetic patients among all positive predictions.
Confusion Matrix: Provides a detailed breakdown of true positive, true negative, false positive, and false negative predictions.
ROC Curve: An ROC curve is plotted to visualize the model's performance in terms of true positive rate (sensitivity) versus false positive rate (1-specificity). The area under the ROC curve (AUC-ROC) is calculated to quantify the model's discriminative power.

## Results and Insights
The logistic regression model achieved an accuracy score of 72%, a recall score of 82%, and a precision score of 56% on the test dataset.
Feature importance analysis revealed that Glucose and BMI were the most significant predictors of diabetes status.
