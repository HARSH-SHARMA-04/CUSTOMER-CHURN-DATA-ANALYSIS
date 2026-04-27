# 📊 Customer Churn Data Analysis

## 📌 Project Overview

Customer churn is one of the biggest challenges for subscription-based and service-driven businesses. This project focuses on analyzing customer churn data to identify the key factors that lead customers to discontinue a service.

Using data analytics, visualization, and machine learning techniques, the project uncovers hidden patterns in customer behavior and provides actionable insights to improve customer retention strategies. :contentReference[oaicite:0]{index=0}

---

## 🎯 Objectives

- Understand customer behavior and churn trends  
- Perform Exploratory Data Analysis (EDA)  
- Clean and preprocess raw data  
- Analyze relationships between features and churn  
- Build predictive machine learning models  
- Generate business recommendations to reduce churn  
- Create interactive dashboards for better decision-making  

---

## 🗂️ Dataset Information

**Source:** Telecom Customer Churn Dataset (Kaggle / Public Dataset)

### Features Included:

- 👤 Customer Demographics  
  - Gender  
  - Senior Citizen  
  - Partner / Dependents  

- 📄 Account Information  
  - Tenure  
  - Contract Type  
  - Payment Method  

- 📞 Services Used  
  - Internet Service  
  - Online Security  
  - Tech Support  
  - Streaming Services  

- 💳 Billing Details  
  - Monthly Charges  
  - Total Charges  

- 🎯 Target Variable  
  - Churn (Yes / No)

---

## 🛠️ Tech Stack

### Programming Language
- Python 🐍

### Libraries Used

- `pandas` → Data Cleaning & Manipulation  
- `numpy` → Numerical Operations  
- `matplotlib` → Data Visualization  
- `seaborn` → Statistical Charts  
- `scikit-learn` → Machine Learning Models  
- `plotly` / `tableau` → Interactive Dashboarding  

---

## 📊 Exploratory Data Analysis (EDA)

Performed multiple visual analyses to understand churn behavior:

- Churn vs Non-Churn Distribution  
- Contract Type vs Churn  
- Monthly Charges vs Churn  
- Tenure vs Churn  
- Payment Method vs Churn  
- Senior Citizen vs Churn  
- Services Used vs Churn  
- Gender vs Churn  

Dashboard visualizations confirm that month-to-month customers, high monthly charges, and electronic check users are more likely to churn. :contentReference[oaicite:1]{index=1}

---

## 🤖 Machine Learning Workflow

### Steps:

1. Data Cleaning  
2. Handling Missing Values  
3. Label Encoding / One-Hot Encoding  
4. Feature Scaling  
5. Train-Test Split  
6. Model Training  
7. Model Evaluation  

### Models Used:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost (Optional)

---

## 📈 Key Insights

✅ Customers with **Month-to-Month contracts** show highest churn rate  
✅ Long-term contracts significantly reduce churn  
✅ Higher monthly charges increase churn probability  
✅ Customers using **Electronic Check** churn more frequently  
✅ Lack of Tech Support / Online Security increases churn risk  
✅ Senior citizens show relatively higher churn tendency  

---

## 📌 Business Recommendations

- Offer discounts for yearly contracts  
- Improve onboarding for new customers  
- Promote tech support bundles  
- Provide loyalty rewards for long-tenure customers  
- Investigate issues with electronic payment users  
- Build personalized retention campaigns using ML predictions  

---

## 📷 Dashboard Preview

Interactive Tableau dashboard included for visual churn insights. :contentReference[oaicite:2]{index=2}

---

## 🚀 How to Run Project

```bash
# Clone Repository
git clone <your-repo-link>

# Install Dependencies
pip install -r requirements.txt

# Run Notebook
jupyter notebook ChurnDA.ipynb
