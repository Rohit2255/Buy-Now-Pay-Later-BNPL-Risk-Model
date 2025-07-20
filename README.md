# 💳 Buy Now Pay Later (BNPL) Risk Prediction Model

### 📅 Project: Day 15 of [#100DaysOfDataScience](https://www.linkedin.com/in/rohit-kumar-yadav-b97360194/)
### 👤 Author: [Rohit Kumar Yadav](https://www.linkedin.com/in/rohit-kumar-yadav-b97360194/)

---

## 📌 Overview

In this project, I built a **credit risk prediction model** to assess whether a borrower will default, mimicking a **Buy Now Pay Later (BNPL)** scenario. The model was trained using one of the largest publicly available lending datasets — the **LendingClub dataset**, which contains over **2 million real loan records**.

This type of model is highly relevant in **FinTech**, where companies like Klarna, Affirm, and Afterpay assess borrower risk instantly before approving micro-loans for e-commerce purchases.

---

## 🧠 Problem Statement

**Objective:**  
Predict the likelihood that a loan applicant will **default** using only **pre-loan features** — the kind available before a loan decision is made.

---

## 🗂 Dataset

- **Source**: [LendingClub Public Loan Data](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
- **Size**: ~2 million records
- **Features Used**:
  - Loan Amount, Term, Interest Rate
  - Installment, Grade, Sub-Grade
  - Employment Length, Annual Income
  - Home Ownership, Verification Status
  - Loan Purpose, Address State
  - Credit History Metrics: DTI, Revolving Utilization, Open Accounts, Total Accounts
- **Target Variable**: `default` (binary: 1 if borrower defaulted, 0 otherwise)

---

## ⚙️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Core programming |
| **Pandas** | Data manipulation |
| **Scikit-learn** | Modeling and evaluation |
| **Matplotlib** | Visualization |
| **Joblib** | Model export |

---

## 🔍 Steps Performed

1. **Data Loading & Selection**
   - Extracted a subset of relevant features from the massive LendingClub dataset
2. **EDA & Preprocessing**
   - Basic cleaning and preparation
   - Filtered only pre-loan features to simulate real-world risk prediction
3. **Target Variable Definition**
   - Defined `default` as the binary target (approx. 21.5% default rate)
4. **Modeling**
   - Logistic Regression model trained and tuned for stability and explainability
5. **Model Evaluation**
   - Used **Calibration Curve** and **Precision-Recall Curve** to assess performance
6. **Model Export**
   - Pipeline saved using `joblib` for deployment use
7. **SHAP Skipped**
   
---

## 📈 Results

- **Model Type**: Logistic Regression  
- **Performance**:
  - Well-calibrated predictions via calibration plot
  - Average Precision Score on test data used for validation
- **Interpretability**: Logistic model provides coefficients useful for understanding direction of impact


---

## 🚀 Future Scope

- Improve performance with XGBoost or LightGBM
- Add SHAP-based interpretability
- Build a Streamlit app for interactive predictions
- Integrate a frontend UI to simulate real-time loan approvals

---

## 🤝 Let's Connect

This project is part of my [#100DaysOfDataScience](https://www.linkedin.com/in/rohit-kumar-yadav-b97360194/) challenge.  
I’m exploring real-world use cases of machine learning in **Finance, Lending, and Risk Analytics**.

📩 Feel free to connect or collaborate!  
📧 ry661432@gmail.com 
🌐 [LinkedIn](https://www.linkedin.com/in/rohit-kumar-yadav-b97360194/) | [GitHub](https://github.com/rohit2255)

---

## 🏷️ Tags

`#DataScience` `#FinanceAI` `#BNPL` `#RiskModel` `#MachineLearning` `#Python` `#LendingClub` `#CreditRisk` `#FinTech`



