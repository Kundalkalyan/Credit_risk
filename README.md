# Credit Risk Prediction using Machine Learning

## 📌 Project Overview

This project builds a Machine Learning model to predict whether a person is likely to default on a loan (credit risk) using financial and personal data. The goal is to help financial institutions make better lending decisions by identifying high-risk applicants.

The project uses classification algorithms such as Logistic Regression and Random Forest to analyze patterns in the dataset and predict loan default probability.

---

## 🎯 Objective

To develop a predictive model that classifies loan applicants into:

* Low Risk (No Default)
* High Risk (Default)

---

## 📊 Dataset

The dataset contains information about individuals’ financial status and loan history.

### Key Features:

* Person age
* Income
* Employment length
* Home ownership
* Loan intent
* Loan amount
* Interest rate
* Credit history length
* Previous default history

### Target Variable:

* `loan_status`

  * 0 → No Default (Good credit)
  * 1 → Default (Bad credit)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Jupyter Notebook / VS Code

---

## 🧠 Machine Learning Models

* Logistic Regression
* Random Forest Classifier

---

## 🔄 Project Workflow

### 1. Data Loading

* Import dataset using Pandas

### 2. Data Preprocessing

* Handle missing values
* Convert categorical data into numerical format using Label Encoding
* Feature scaling using StandardScaler

### 3. Feature & Target Split

* Features (X): All input variables
* Target (y): Loan status

### 4. Train-Test Split

* 80% Training data
* 20% Testing data

### 5. Model Training

* Logistic Regression model trained for baseline performance
* Random Forest used for improved accuracy

### 6. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
