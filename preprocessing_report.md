# Customer Churn Prediction - Preprocessing Report

## Project Title

**Customer Churn Prediction using Data Preprocessing & Feature Engineering**

---

# Project Overview

The purpose of this project is to preprocess customer churn data before applying machine learning algorithms. Data preprocessing improves data quality by converting categorical data into numerical values, scaling numerical features, detecting outliers, creating new features, selecting important features, and building a complete preprocessing pipeline.

---

# Dataset Information

* Dataset Name: customer_churn.csv
* Total Rows: 500
* Total Columns: 9

### Dataset Features

* CustomerID
* Tenure
* MonthlyCharges
* TotalCharges
* Contract
* PaymentMethod
* PaperlessBilling
* SeniorCitizen
* Churn


# Preprocessing Steps

## 1. Dataset Exploration

The dataset was loaded using Pandas. Basic information such as dataset shape, column names, data types, summary statistics, and missing values was checked.


## 2. Categorical Data Encoding

Categorical features were converted into numerical values.

Encoding techniques used:

* Label Encoding
* One-Hot Encoding

Columns encoded:

* Contract
* PaymentMethod
* PaperlessBilling
* Churn



## 3. Feature Scaling

Numerical columns were scaled using:

* Min-Max Scaling
* Standard Scaling

Scaled Features:

* Tenure
* MonthlyCharges
* TotalCharges



## 4. Outlier Detection

Outliers were identified using:

* IQR Method
* Z-Outlier
