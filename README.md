# Telecom Customer Churn Analysis

Analyzing customer churn data from a telecom company to uncover key factors that influence customer attrition and provide actionable business insights for improving retention strategies.

---

## 📁 Project Overview

Customer churn — when customers stop using a service — is a major concern for subscription-based businesses. In the telecom industry, high churn leads to substantial revenue loss and increased acquisition costs. This project explores a real-world telecom dataset to identify patterns and factors associated with customer churn using Exploratory Data Analysis (EDA).

---

## 📊 Objective

- Understand overall churn trends and distribution
- Identify customer segments with high churn rates
- Discover which services or features are most associated with churn
- Quantify revenue loss due to churn
- Provide strategic business recommendations

---

## 📦 Dataset

- Source: [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Records: 7,043 customers
- Features: Customer demographics, account information, service usage, and churn label

---

## 🧰 Tools and Libraries

- Python (Google Colab)
- Pandas, NumPy
- Matplotlib, Seaborn
- CSV data handling

---

## 🔍 Key Findings

- **Churn Rate**: Approximately **26.54%** of customers have churned.
- **Tenure**: Customers with a short tenure (1–2 months) are **far more likely to churn** than long-term users.
- **Contract Type**: Customers with **month-to-month contracts** churn the most compared to yearly contracts.
- **Senior Citizens**: Show a **slightly higher churn rate** than younger customers.
- **Services**:
  - Non-churners often have **PhoneService, DSL Internet**, and **OnlineSecurity** enabled.
  - Churners are less likely to subscribe to **OnlineBackup, TechSupport, StreamingTV**.
- **Payment Method**: Customers using **Electronic Check** have the **highest churn** among all payment methods.
- **Revenue Impact**:
  - Revenue lost from churned customers: **2,862,926.90**
  - Revenue from active customers: **13,193,241.80**

---

## 💡 Business Insights & Recommendations

1. **Churn is a major issue** – over 25% churn rate results in significant revenue loss.
2. **Focus on early retention** – customers are most vulnerable in the first few months.
3. **Promote longer contracts** – 1- and 2-year contracts have much lower churn rates.
4. **Bundle value-added services** – customers with OnlineSecurity and TechSupport churn less.
5. **Address payment pain points** – investigate why electronic check users are leaving.
6. **Targeted support for senior citizens** – may benefit from simplified plans or personalized outreach.
