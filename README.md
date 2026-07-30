# 📊 Telco Customer Churn Analysis

## 📌 Project Overview

This project explores customer churn using exploratory data analysis (EDA), descriptive statistics, machine learning, and business intelligence visualization.

The objective is to identify the factors associated with customer churn and demonstrate how statistical analysis and data visualization can support business decision-making.

## ⭐ Project Highlights

* Performed exploratory data analysis on 7,043 customer records.
* Used descriptive statistics to identify churn patterns.
* Built an interactive Power BI dashboard with DAX measures.
* Translated analytical findings into business insights for customer retention.
---

## 🎯 Business Problem

Customer churn is one of the biggest challenges for subscription-based businesses. Losing customers reduces revenue and increases the cost of acquiring new customers.

This project aims to answer the following questions:

* What percentage of customers leave the company?
* Do customers with shorter tenure churn more?
* Does contract type influence customer churn?
* Are higher monthly charges associated with churn?
* Which customer characteristics are associated with higher churn risk?

---

## 📂 Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains **7,043 customer records** and **21 features**, including:

* Customer demographics
* Contract information
* Internet services
* Billing information
* Customer churn status

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook (Kaggle)
* Microsoft Power BI
* DAX Measures

---

## 📊 Statistical Analysis Performed

The project includes:

* Data exploration
* Data inspection
* Descriptive statistics
* Group comparisons
* Cross-tabulation analysis
* Customer churn analysis
* Pattern identification using statistical summaries

---

## 🔍 Key Findings

### 1. Customer Churn

* **26.54%** of customers left the company.
* **73.46%** remained customers.

### 2. Customer Tenure

Customers who churned had a much lower average tenure compared with customers who stayed.

| Customer Status |   Average Tenure |
| --------------- | ---------------: |
| Stayed          | **37.57 months** |
| Churned         | **17.98 months** |

### 3. Contract Type

Customer churn varied significantly by contract type.

| Contract       | Churn Rate |
| -------------- | ---------: |
| Month-to-month | **42.71%** |
| One year       | **11.27%** |
| Two year       |  **2.83%** |

### 4. Monthly Charges

Customers who churned paid higher monthly charges on average.

| Customer Status | Average Monthly Charges |
| --------------- | ----------------------: |
| Stayed          |              **$61.27** |
| Churned         |              **$74.44** |

---

## 💡 Business Insights

The analysis suggests that:

* Newer customers are more likely to leave.
* Customers on month-to-month contracts have the highest churn rate.
* Customers with higher monthly charges show increased churn tendency.
* Longer customer relationships are associated with lower churn.
* Customer retention strategies should focus on early-stage customers.

---

## 🤖 Machine Learning (Future Work)

Future improvements include:

* Data cleaning improvements
* Feature engineering
* Hypothesis testing
* Logistic Regression
* Decision Trees
* Random Forest
* XGBoost
* Model evaluation using:

  * Precision
  * Recall
  * F1-score
  * ROC-AUC

---

## 📊 Power BI Dashboard

An interactive dashboard was created using Microsoft Power BI to analyze customer churn patterns and present business insights visually.

### Key Metrics

* Total Customers: **7,043**
* Total Churned Customers: **1,869**
* Churn Rate: **26.54%**

### Dashboard Preview

![Telco Customer Churn Dashboard](dashboard.png)

### Dashboard Features

* KPI cards for customer metrics
* Churn rate visualization
* Customer churn analysis by contract type
* Customer churn analysis by tenure
* Monthly charge analysis

---

## 📁 Repository Structure

```text
├── Telco_Customer_Churn_Analysis.ipynb
├── Telco_Customer_Churn_Dashboard.pbix
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── dashboard.png
└── README.md
```

---

## 👩‍💻 Author

**Bhawanjeet**

This project was completed as part of my Data Science learning journey and demonstrates the application of statistics, exploratory data analysis, machine learning concepts, and business intelligence tools to solve real-world business problems.
