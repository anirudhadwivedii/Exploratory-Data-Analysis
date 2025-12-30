# Bank Loan Approval – Exploratory Data Analysis

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a bank loan dataset to understand the factors influencing loan approval decisions.

## 📂 Dataset
The dataset contains applicant demographic, financial, and property-related information along with loan approval status.

## 🧹 Data Cleaning & Preprocessing
- Removed irrelevant identifier column (Loan_ID)
- Handled missing values using mode and median
- Corrected data types and ensured logical consistency
- Converted Dependents into numeric form

## 📊 Exploratory Data Analysis
### Univariate Analysis
- Analyzed distributions of categorical and numerical variables
- Observed skewness and outliers in income and loan amount

### Bivariate Analysis
- Studied relationships between Loan_Status and other features
- Credit_History found to be the strongest predictor
- Property_Area and Education show moderate influence

## 🔍 Key Insights
- Applicants with good credit history have significantly higher approval rates
- Urban and Semiurban properties show higher loan approvals
- Income and loan amount alone do not guarantee approval
- Dependents have a weak to moderate impact

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🚀 Conclusion
EDA reveals that credit history is the most influential factor in loan approval decisions, making the dataset suitable for predictive modeling.

---
