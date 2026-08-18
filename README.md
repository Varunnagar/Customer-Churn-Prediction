# 📊 Customer Churn Prediction Model

## 📌 Project Overview

Customer churn is a major challenge for businesses because losing existing customers can directly affect revenue and business growth.

This project focuses on building a **Machine Learning classification model** that predicts whether a customer is likely to **churn (leave the company)** or **stay**.

The project uses the **Telco Customer Churn dataset**, which contains customer demographic information, services, contract details, payment methods, tenure, and billing information.

The complete project follows a structured Machine Learning workflow, starting from data cleaning and exploratory data analysis and progressing to model training, evaluation, overfitting/underfitting analysis, and hyperparameter tuning.

---

# 🎯 Project Objectives

The main objectives of this project are:

- Predict whether a customer is likely to churn.
- Understand the factors that influence customer churn.
- Clean and preprocess customer data.
- Analyze customer behavior using Exploratory Data Analysis (EDA).
- Convert categorical variables into numerical values using Label Encoding.
- Handle class imbalance using SMOTE.
- Train multiple Machine Learning classification models.
- Compare model performance using different evaluation metrics.
- Identify possible overfitting and underfitting.
- Improve model performance using Hyperparameter Tuning.

---

# 📂 Dataset

The project uses the **Telco Customer Churn dataset**.

The dataset contains approximately:

- **7,043 customers**
- **21 columns**

The dataset contains information about:

- Customer demographics
- Customer services
- Contract type
- Payment method
- Customer tenure
- Monthly charges
- Total charges
- Customer churn status

---

# 📋 Important Dataset Columns

| Column | Description |
|---|---|
| `customerID` | Unique identifier for each customer |
| `gender` | Customer gender |
| `SeniorCitizen` | Indicates whether the customer is a senior citizen |
| `Partner` | Whether the customer has a partner |
| `Dependents` | Whether the customer has dependents |
| `tenure` | Number of months the customer has stayed with the company |
| `PhoneService` | Whether the customer has phone service |
| `MultipleLines` | Whether the customer has multiple phone lines |
| `InternetService` | Type of internet service |
| `OnlineSecurity` | Whether online security service is subscribed |
| `OnlineBackup` | Whether online backup is subscribed |
| `DeviceProtection` | Whether device protection is subscribed |
| `TechSupport` | Whether technical support is subscribed |
| `StreamingTV` | Whether streaming TV service is subscribed |
| `StreamingMovies` | Whether streaming movie service is subscribed |
| `Contract` | Customer contract type |
| `PaperlessBilling` | Whether the customer uses paperless billing |
| `PaymentMethod` | Customer payment method |
| `MonthlyCharges` | Monthly amount charged to the customer |
| `TotalCharges` | Total amount charged to the customer |
| `Churn` | Whether the customer left the company |

---

# 🎯 Target Variable

The target variable is:

```text
Churn
