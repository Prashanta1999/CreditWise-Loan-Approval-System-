# CreditWise Loan Approval System 

## Overview

The **CreditWise Loan Approval System** is a Supervised Machine Learning Classification Learning-based application designed to automate the loan approval process for financial institutions. The system analyzes applicant information and predicts whether a loan application should be **Approved** or **Rejected** before final human verification.

This project aims to reduce manual effort, improve decision consistency, minimize bias, and help financial organizations make faster and more accurate lending decisions.

---

## Problem Statement

Traditional loan approval processes rely heavily on manual verification of customer documents, including income proofs, employment details, and credit history. This approach is often:

* Time-consuming
* Prone to human bias
* Inconsistent across different loan officers
* Unable to efficiently handle large volumes of applications

As a result:

* Eligible customers may be rejected.
* High-risk customers may receive loan approvals.
* Financial institutions face revenue loss and increased credit risk.

The objective of this project is to build an intelligent loan approval system that predicts loan eligibility using historical customer data.

---

## Project Workflow

### 1. Data Collection

* Load historical loan application data.
* Explore dataset structure and features.

### 2. Data Preprocessing

* Handle missing values.
* Remove duplicates.
* Encode categorical variables.
* Feature scaling and normalization.

### 3. Exploratory Data Analysis (EDA)

* Analyze applicant demographics.
* Study loan approval patterns.
* Visualize correlations and feature distributions.

### 4. Feature Engineering

* Create meaningful derived features.
* Select important predictors.

### 5. Model Building

Train and evaluate multiple machine learning algorithms:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost
* Gradient Boosting
* Support Vector Machine (SVM)

### 6. Model Evaluation

Performance metrics used:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

### 7. Prediction System

The final model predicts:

* **Approved (1)**
* **Rejected (0)**

for new loan applicants.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Jupyter Notebook

---

## Project Structure

```text
CreditWise-Loan-System/
│
├── data/                # Ignored via .gitignore , you can download data from kaggle
│
├── notebooks/
│   └── Loan_Approval_Analysis.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── app/
│   └── prediction_app.py
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

## Installation



### Navigate to Project Directory

```bash
cd CreditWise-Loan-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Project

### Jupyter Notebook

```bash
jupyter notebook
```

### Python Application

```bash
python prediction_app.py
```

---

## Expected Outcome

The system will:

* Automate preliminary loan screening.
* Reduce approval processing time.
* Improve decision accuracy.
* Minimize financial risk.
* Support fair and data-driven lending decisions.

---

## Future Enhancements

* Deploy using Flask or FastAPI.
* Build a React frontend dashboard.
* Integrate with bank databases.
* Real-time credit bureau API integration.
* Explainable AI (SHAP/LIME) for decision transparency.

---

## Author

**Prashanta Chowdhury**

Machine Learning & Full Stack Developer

GitHub: https://github.com/Prashanta1999
