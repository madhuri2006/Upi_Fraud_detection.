# Upi_Fraud_detection.
🚀 Project Overview

The goal is to build a machine learning model that classifies UPI transactions as legitimate or fraudulent.
The workflow includes:

Data loading and cleaning

Handling missing values

Encoding categorical features

Feature scaling

Exploratory Data Analysis (EDA)

Feature engineering

Training a Random Forest model

Evaluating accuracy and prediction performance

📊 Dataset

The dataset includes features such as:

Transaction amount

Transaction type

Time and frequency of transactions

User behavior metrics

Device and location attributes

Fraud/non-fraud labels

The dataset used in this project is provided as:
data_set.csv

🧹 Data Preprocessing

Steps performed:

Removed null and inconsistent values

Converted categorical features using Label Encoding

Scaled numerical attributes

Extracted meaningful features (behavioral and transactional)

Outlier analysis and correction

🔍 Model Used: Random Forest Classifier

Random Forest was chosen because:

It handles high-dimensional data well

Reduces overfitting using bagging

Provides high accuracy for classification tasks

Works effectively with non-linear feature interactions

Model includes:

70/30 train-test split

Hyperparameter tuning (if applicable)

Prediction probability scores

📈 Model Evaluation

The model is evaluated using:

Accuracy score

Precision

Recall

F1-score

Confusion Matrix

Classification Report

These metrics help assess fraud detection effectiveness and reduce false positives/negatives.
