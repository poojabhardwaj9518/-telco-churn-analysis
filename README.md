# Telco Customer Churn Analysis

## 📌 Project Overview
Customer churn occurs when customers stop doing business with a company. In the telecom industry, retaining existing customers is often far more cost-effective than acquiring new ones. 

This project analyzes historical telecom customer data to identify key factors influencing customer attrition. By leveraging exploratory data analysis (EDA) and predictive modeling, the goal is to uncover actionable insights that can help the business develop targeted retention strategies.

---

## 📊 Dataset Description
The dataset used for this analysis is `Telco-Customer-Churn (2).csv`. It contains demographic, account, and services information for telecom customers.

Key features include:
* **Demographics:** Gender, Senior Citizen status, Partner, and Dependents.
* **Services:** Phone service, Multiple lines, Internet service (DSL, Fiber optic, No), Online security, Online backup, Device protection, Tech support, Streaming TV, and Streaming Movies.
* **Account Information:** Customer tenure (months), Contract type (Month-to-month, One year, Two year), Paperless billing, Payment method, Monthly charges, and Total charges.
* **Target Variable:** `Churn` (Whether the customer left within the last month: Yes/No).

---

## 🛠️ Key Insights & Visualizations
*(Note: Based on the analysis screenshots uploaded to the repository)*

* **Contract Type Impact:** Customers on **Month-to-month contracts** exhibit significantly higher churn rates compared to those on one-year or two-year contracts.
* **Tenure:** Newer customers (low tenure months) are at a much higher risk of churning.
* **Internet Service Type:** Customers subscribing to **Fiber Optic** internet service show a disproportionately high churn rate, signaling potential issues with pricing or service satisfaction.
* **Payment Method:** Customers using **Electronic Checks** churn at a higher rate than those utilizing automated payment options (Credit Card/Bank Transfer).

---

## 🚀 Technologies Used
* **Python** (Data manipulation and modeling)
* **Pandas & NumPy** (Data cleaning and preprocessing)
* **Matplotlib & Seaborn** (Data visualization)
* **Scikit-Learn** (Machine learning algorithms and evaluation)
* **Jupyter Notebook** (Interactive development environment)

---

## 📂 Project Structure
```text
├── Telco-Customer-Churn (2).csv       # Raw dataset
├── telco_churn_analysis.ipynb         # Jupyter Notebook with full analysis & code
├── README.md                          # Project documentation
└── Screenshots/                       # Visualizations and dashboard captures
