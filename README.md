# Bank Term Deposit Prediction Using Machine Learning

## Overview

This project focuses on predicting whether a customer will subscribe to a bank term deposit using Machine Learning techniques. The goal is to analyze customer demographic and marketing campaign data and build a predictive model that helps financial institutions identify potential customers for term deposit subscriptions.

The project includes data preprocessing, exploratory data analysis, feature encoding, visualization, and predictive modeling using Logistic Regression.

---

## Problem Statement

Banks conduct marketing campaigns to promote term deposits. However, contacting every customer is expensive and inefficient. By using machine learning, banks can identify customers who are more likely to subscribe, improving marketing efficiency and reducing operational costs.

---

## Dataset Information

The dataset contains customer demographic details, financial information, and marketing campaign records.

### Features Include

* Age
* Job
* Marital Status
* Education
* Default
* Balance
* Housing Loan
* Personal Loan
* Contact Type
* Day
* Month
* Duration
* Campaign
* Previous Outcome
* And other customer-related attributes

### Target Variable

* y

  * Yes → Customer subscribed to term deposit
  * No → Customer did not subscribe

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Preprocessing

* Loaded and explored the dataset.
* Checked for missing values.
* Performed data cleaning.
* Encoded categorical variables using Label Encoding.
* Prepared features and target variable.

### 2. Exploratory Data Analysis

* Analyzed customer demographics.
* Studied relationships between features and subscription status.
* Visualized important trends using charts and graphs.

### 3. Feature Engineering

* Converted categorical columns into numerical format.
* Selected relevant features for prediction.
* Prepared training and testing datasets.

### 4. Model Building

Implemented Logistic Regression for binary classification.

#### Model Configuration

* Algorithm: Logistic Regression
* Train-Test Split: 80:20
* Random State: 42

### 5. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## Machine Learning Pipeline

1. Data Collection
2. Data Cleaning
3. Data Encoding
4. Train-Test Split
5. Model Training
6. Prediction
7. Performance Evaluation

---

## Results

The Logistic Regression model successfully classified customers based on their likelihood of subscribing to a term deposit.

### Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

These metrics help assess the effectiveness of the predictive model and its ability to identify potential subscribers.

---

## Key Learnings

* Data Preprocessing Techniques
* Label Encoding
* Exploratory Data Analysis (EDA)
* Binary Classification
* Logistic Regression
* Model Evaluation
* Customer Behavior Analysis

---

## Business Impact

This model can help banks:

* Improve marketing campaign effectiveness
* Reduce customer acquisition costs
* Increase subscription rates
* Target high-potential customers more efficiently

---

## Conclusion

This project demonstrates how Machine Learning can be applied to banking and financial services to predict customer responses to marketing campaigns. By leveraging Logistic Regression and customer data, banks can make data-driven decisions and improve the success rate of term deposit marketing campaigns.
