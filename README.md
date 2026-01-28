# 💳 CreditWise Loan System

## 📌 Overview
**CreditWise Loan System** is a **Machine Learning–based loan approval system** designed to assist financial institutions in making **fast, accurate, and unbiased loan approval decisions**.

The system analyzes historical loan application data to predict whether a loan should be **Approved (1)** or **Rejected (0)**, serving as a **decision-support tool** before final human verification.

---

## 🏦 Problem Statement
A financial institution operating across **urban and rural regions of India** faced challenges due to manual loan verification processes:

- Creditworthy applicants being rejected → **loss of business**
- High-risk applicants being approved → **financial losses**
- Time-consuming, inconsistent, and biased decisions

To overcome these issues, the institution required an **intelligent Machine Learning–based solution** to automate and support loan approval decisions.

---

## 🎯 Project Objective
- Build a **binary classification model** to predict loan approval status  
- Reduce manual effort and human bias  
- Improve approval accuracy and risk assessment  

### 🎯 Target Variable
- **Loan_Approved**
  - `1` → Approved  
  - `0` → Rejected  

---

## 📊 Dataset Description
Each row represents a **loan applicant** with demographic, financial, and credit-related information.

### 🔹 Features
| Column Name | Description |
|------------|------------|
| Applicant_ID | Unique applicant identifier |
| Applicant_Income | Monthly income of applicant |
| Coapplicant_Income | Monthly income of co-applicant |
| Employment_Status | Salaried / Self-Employed / Business |
| Age | Applicant age |
| Marital_Status | Married / Single |
| Dependents | Number of dependents |
| Credit_Score | Credit bureau score |
| Existing_Loans | Number of active loans |
| DTI_Ratio | Debt-to-Income ratio |
| Savings | Savings balance |
| Collateral_Value | Value of collateral |
| Loan_Amount | Requested loan amount |
| Loan_Term | Loan duration (months) |
| Loan_Purpose | Home / Education / Personal / Business |
| Property_Area | Urban / Semi-Urban / Rural |
| Education_Level | Graduate / Postgraduate / Undergraduate |
| Gender | Male / Female |
| Employer_Category | Govt / Private / Self |

---

## 🧠 Machine Learning Approach
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Encoding & Scaling  
4. Model Training & Comparison  
   - Logistic Regression  
   - K-Nearest Neighbors (KNN)  
   - Naive Bayes  
5. Model Evaluation & Selection  

### 📈 Model Selection
**Naive Bayes achieved higher Precision and Recall scores** compared to Logistic Regression and KNN, making it the final model.

➡️ **Final Model Used:** Naive Bayes  

---

## 🛠️ Tech Stack
- Python  
- NumPy, Pandas, Scikit-learn  
- Matplotlib, Seaborn  

---

## 🌐 Deployment
The trained Naive Bayes model is prepared for deployment using **Streamlit** for real-time loan approval prediction.

---

## 📌 Project Status
✅ Project Completed
