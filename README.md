# 🏦 Bank Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn is one of the biggest challenges in the banking industry. Losing existing customers not only reduces revenue but also increases customer acquisition costs. This project uses Machine Learning techniques to predict whether a customer is likely to leave the bank based on their demographic information, account details, and banking behavior.

The goal is to help banks identify customers who are at high risk of churn so they can implement targeted retention strategies.

---

## 🎯 Objectives

* Analyze customer data to understand churn patterns.
* Perform data cleaning and preprocessing.
* Explore customer behavior through visualizations.
* Build and compare multiple machine learning models.
* Evaluate model performance using classification metrics.
* Generate actionable business insights.

---

## 📂 Dataset

The dataset contains customer information such as:

* Customer ID
* Credit Score
* Geography
* Gender
* Age
* Tenure
* Account Balance
* Number of Products
* Credit Card Status
* Active Member Status
* Estimated Salary
* Churn Status (Target Variable)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

The project includes:

* Missing value analysis
* Data cleaning
* Feature distribution
* Correlation analysis
* Churn analysis by:

  * Age
  * Geography
  * Gender
  * Credit Score
  * Balance
  * Number of Products
  * Active Membership

---

## 🤖 Machine Learning Models

The following classification models were implemented:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

---

## 📈 Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

---

## 📁 Project Structure

```text
Bank-Customer-Churn-Prediction/
│
├── data/
│   └── churn.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── images/
│
├── requirements.txt
├── README.md
└── .gitignore
```

## 📊 Results

The machine learning models were trained and evaluated to identify customers likely to churn. Model performance was compared using multiple evaluation metrics, and the best-performing model can help banks proactively target at-risk customers with personalized retention strategies.

---

## 💼 Business Impact

This project enables banks to:

* Improve customer retention
* Reduce customer acquisition costs
* Identify high-risk customers
* Support data-driven decision-making
* Increase customer lifetime value

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Model deployment using Streamlit or Flask
* Explainable AI using SHAP
* Real-time prediction API
* Cloud deployment using AWS or Azure
