# 📊 Telco Customer Churn Analysis

## 📌 Project Overview

This project analyzes customer churn using **Exploratory Data Analysis (EDA), descriptive statistics, machine learning, and business intelligence visualization**. The objective is to identify the key factors associated with customer churn and demonstrate how data analytics can support customer retention and business decision-making.

The project follows a complete end-to-end data science workflow, from data preprocessing and statistical analysis to predictive modeling and interactive dashboard development.

---

## 🚀 Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning & Preprocessing
* Feature Engineering
* Descriptive Statistics
* Data Visualization
* Logistic Regression
* Random Forest
* XGBoost
* Model Evaluation
* Feature Importance Analysis
* Microsoft Power BI
* Business Intelligence & Business Insights

---

## 🎯 Business Problem

Customer churn is one of the biggest challenges for subscription-based businesses. Losing customers reduces revenue and increases customer acquisition costs.

This project aims to answer the following business questions:

* What percentage of customers leave the company?
* Do customers with shorter tenure churn more frequently?
* Does contract type influence customer churn?
* Are higher monthly charges associated with churn?
* Which customer characteristics are associated with higher churn risk?

---

## 📂 Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains **7,043 customer records** and **21 customer attributes**, including:

* Customer demographics
* Contract information
* Internet services
* Billing information
* Payment methods
* Customer churn status

---

## 🛠️ Technologies Used

### Programming & Analysis

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook (Kaggle)

### Business Intelligence

* Microsoft Power BI
* DAX Measures

---

## 📊 Exploratory Data Analysis

The analysis included:

* Data inspection
* Missing value handling
* Data type conversion
* Descriptive statistics
* Customer segmentation
* Cross-tabulation analysis
* Churn pattern identification
* Feature engineering

---

## 🤖 Machine Learning Models

Three machine learning models were developed and compared:

1. Logistic Regression
2. Random Forest
3. XGBoost

The dataset was prepared using:

* Data cleaning
* One-Hot Encoding
* Train-Test Split
* Feature Engineering

---

## 📈 Model Performance

| Model               |   Accuracy | Churn Precision | Churn Recall | Churn F1 |    ROC-AUC |
| ------------------- | ---------: | --------------: | -----------: | -------: | ---------: |
| Logistic Regression | **80.24%** |         **65%** |      **57%** |  **61%** | **0.8366** |
| Random Forest       |     79.00% |             63% |          49% |      55% |     0.8147 |
| XGBoost             |     79.00% |             62% |          53% |      57% |     0.8315 |

### Best Performing Model

**Logistic Regression** achieved the strongest overall performance on this dataset, providing the highest accuracy and ROC-AUC among the evaluated models.

---

## 📊 Key Statistical Findings

### Customer Churn

* **26.54%** of customers left the company.
* **73.46%** remained customers.

### Customer Tenure

| Customer Status |   Average Tenure |
| --------------- | ---------------: |
| Stayed          | **37.57 months** |
| Churned         | **17.98 months** |

Customers who churned had significantly shorter tenure.

### Contract Type

| Contract Type  | Churn Rate |
| -------------- | ---------: |
| Month-to-month | **42.71%** |
| One year       | **11.27%** |
| Two year       |  **2.83%** |

### Monthly Charges

| Customer Status | Average Monthly Charges |
| --------------- | ----------------------: |
| Stayed          |              **$61.27** |
| Churned         |              **$74.44** |

Customers with higher monthly charges were more likely to churn.

---

## 🔍 Feature Importance

The Logistic Regression model identified several important factors associated with customer churn.

Top positive churn indicators included:

* Fiber optic internet service
* Electronic check payment method
* Paperless billing
* Multiple phone lines
* Senior citizen status

These insights can help businesses identify customers at higher risk of leaving and design targeted retention strategies.

---

## 💡 Business Insights

The analysis suggests that:

* Customers with shorter tenure are more likely to churn.
* Month-to-month contracts have the highest churn rate.
* Customers paying higher monthly charges tend to churn more frequently.
* Longer customer relationships are associated with lower churn.
* Customer retention efforts should focus on early-stage customers.

---

## 💼 Business Recommendations

Based on the statistical analysis and machine learning results:

* Focus retention efforts on new customers with shorter tenure.
* Encourage customers to move from month-to-month contracts to longer-term contracts.
* Investigate customer experience among fiber optic users.
* Monitor customers using electronic check payment methods.
* Use predictive models to identify customers at high risk of churn before they leave.
* Combine predictive analytics with business dashboards to support data-driven retention strategies.

---

## 📊 Power BI Dashboard

An interactive dashboard was developed in Microsoft Power BI to visualize customer churn patterns and business metrics.

### Dashboard Features

* KPI Cards
* Customer Churn Rate
* Customer Distribution
* Contract Type Analysis
* Monthly Charges Analysis
* Customer Tenure Analysis
* Interactive Filtering

### Dashboard Preview

![Telco Customer Churn Dashboard](dashboard.png)

---

## 📁 Repository Structure

```text
Telco-Customer-Churn-Analysis
│
├── Telco_Customer_Churn_Analysis.ipynb
├── Telco_Customer_Churn_Dashboard.pbix
├── dashboard.png
└── README.md
```

---

## ✅ Conclusion

This project demonstrates a complete end-to-end data science workflow, including exploratory data analysis, statistical analysis, machine learning, and business intelligence visualization.

Three classification models were evaluated to predict customer churn. Logistic Regression achieved the best overall performance, while feature importance analysis identified the major factors associated with churn. The results illustrate how predictive analytics can support customer retention strategies and improve business decision-making.

---

## 👩‍💻 Author

**Bhawanjeet**

This project was completed as part of my Data Science learning journey and demonstrates practical applications of statistics, machine learning, and business intelligence for solving real-world business problems.
