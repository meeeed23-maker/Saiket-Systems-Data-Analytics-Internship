# 📊 Telco Customer Churn Analysis - SaiKet Systems Internship

![Notebooks CI](hhttps://github.com/meeeed23-maker/Saiket-Systems-Data-Analytics-Internship.git/actions/workflows/run-internship-tasks.yml/badge.svg)

## 📌 Project Overview
This repository contains the complete Data Analytics & Business Analysis project completed during my internship at **SaiKet Systems**. The goal is to analyze customer churn in a telecommunications company and provide actionable insights to reduce customer loss.

## 🎯 Business Problem
A telecom company is losing approximately **26.5% of its customers**. The objective is to understand *why* they leave and identify the profiles of at-risk customers.

## 📂 Project Structure
- **Task 1 - Data Understanding:** Loading the dataset, checking data types, and identifying initial missing values.
- **Task 2 - Data Cleaning:** Handling hidden nulls in `TotalCharges`, standardizing columns, and preparing data for analysis.
- **Task 3 - Exploratory Data Analysis (EDA):** Statistical summary and visualizations (Pie charts, Histograms, Boxplots).
- **Task 4 - Customer Segmentation:** Visualizing customer distribution by tenure using Donut Charts and Clustered Bar Charts.
- **Task 5 - Advanced Analysis:** Cross-analysis of churn by demographics, contract types, and payment methods.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Google Colab
- **CI/CD:** GitHub Actions (auto-execution of notebooks)

## 💡 Key Insights Discovered
- **The "New Customer" Risk:** Customers within their first 12 months represent the highest churn risk.
- **Contract is King:** Customers on a "Month-to-month" contract churn massively compared to those on 1 or 2-year contracts.
- **Payment Method:** Customers using "Electronic check" are much more likely to churn than those on automatic payment.
- **The Ultimate Red Flag:** New customers on a "Month-to-month" contract have a churn rate of over **51%**.

## 📈 Business Recommendations
1. **Focus on Onboarding:** Implement a loyalty program for the first 12 months.
2. **Incentivize Long-Term Contracts:** Offer discounts to push customers toward 1 or 2-year commitments.
3. **Promote Automatic Payments:** Encourage customers to switch from Electronic Check to automatic payments.

## 🚀 How to Run Locally
```bash
pip install -r requirements.txt
jupyter notebook