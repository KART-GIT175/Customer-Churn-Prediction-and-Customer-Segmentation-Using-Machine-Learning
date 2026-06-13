# Customer Churn Prediction and Customer Segmentation using Machine Learning

## Overview

This project focuses on predicting customer churn in the telecom industry and identifying customer segments using machine learning techniques.

The goal is to help businesses identify customers who are likely to leave the service and understand different customer groups for better retention strategies.

---

## Dataset

Dataset: Telco Customer Churn Dataset

The dataset contains customer demographic information, subscription details, billing information, and churn status.

---

## Data Preprocessing

The following preprocessing steps were performed:

* Removed unnecessary columns
* Converted TotalCharges to numeric format
* Handled missing values
* Applied categorical encoding using one-hot encoding
* Feature scaling using StandardScaler
* Train-Test Split

---

## Machine Learning Models Used

### Classification Models

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Gaussian Naive Bayes
* Decision Tree Classifier
* Support Vector Machine (SVM)
* Random Forest Classifier
* Gradient Boosting Classifier
* AdaBoost Classifier
* XGBoost Classifier

---

## Model Evaluation

Models were evaluated using:

* Classification Report
* Precision
* Recall
* F1-Score
* Cross Validation

Cross-validation was used to measure model stability and generalization performance.

---

## Ensemble Learning

A Stacking Classifier was implemented by combining multiple machine learning algorithms to improve prediction performance.

Base Learners:

* KNN
* Decision Tree
* Random Forest
* SVM
* Logistic Regression
* Gradient Boosting
* AdaBoost
* XGBoost
* Naive Bayes

Meta Learner:

* K-Nearest Neighbors (KNN)

---

## Customer Segmentation

### K-Means Clustering

Used to divide customers into different groups based on behavioral patterns.

### DBSCAN Clustering

Used for density-based customer segmentation and outlier detection.

---

## Dimensionality Reduction

### Principal Component Analysis (PCA)

PCA was used to reduce feature dimensions and visualize customer clusters efficiently.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Data Transformation
4. Feature Engineering
5. Feature Scaling
6. Model Training
7. Model Evaluation
8. Cross Validation
9. Ensemble Learning
10. Customer Segmentation
11. PCA Visualization

---

## Future Improvements

* Hyperparameter Tuning using GridSearchCV
* Hyperparameter Tuning using RandomizedSearchCV
* Deployment using Streamlit
* Advanced Customer Retention Dashboard

---

## Author

Kartik Saxena
B.Tech Computer Science Student
Machine Learning Enthusiast
