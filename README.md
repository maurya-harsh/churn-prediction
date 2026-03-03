<div align="center">

# 📊 Integrated Customer Churn Prediction & Retention Analytics

**A Hybrid Approach Using Ensemble Learning, Survival Analysis, and Voice of Customer (VoC) Insights**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-108A43?style=for-the-badge&logo=xgboost&logoColor=white)

</div>

## 🎯 Project Overview
This research develops a comprehensive, explainable, and multi-dimensional churn prediction framework. It moves beyond identifying *who* will churn using Ensemble models to understanding *when* (Survival Analysis) and *why* (Survey/XAI Analysis), enabling targeted retention strategies across different telecom partners.

## 🗄️ Data Architecture
The framework bridges the gap between predictive accuracy and prescriptive action using a dual-layered data approach:
* **Secondary Dataset (Historical):** 243,553 telecom user records sourced from Kaggle to build predictive models and temporal estimates.
* **Primary Dataset (VoC Survey):** 120 targeted responses capturing qualitative root cause analysis and market sentiment.

## ⚙️ Methodology Pipeline
The workflow is structured into five strategic pillars:

| Phase | Component | Output |
| :--- | :--- | :--- |
| **Phase I** | Market Dynamics | Understanding churn through demographic factors. |
| **Phase II** | Predictive Modeling | Implementing Logistic Regression and Random Forest models. |
| **Phase III** | Survival Analysis | Calculation of Hazard Rates and Estimated Remaining Tenure. |
| **Phase IV** | Interpretability | SHAP Summary Plots and Global Feature Importance. |
| **Phase V** | Strategic Deployment | A/B Testing framework for targeted retention offers. |

## 📈 Key Findings & Impact
* **Detection Superiority:** The Random Forest ensemble demonstrated a high sensitivity to churn, capturing 65% of at-risk customers (Recall).
* **Survival Timeline:** 50% of the customer base is statistically expected to churn by approximately week 1180.
* **Intervention Success:** A/B testing simulated a relative churn reduction of 21.41% among high-risk groups.
* **Financial Viability:** The targeted retention strategies resulted in an estimated retained revenue of ₹10,184,864.42.

## 💻 Tech Stack
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`, `xgboost`, `lightgbm`, `imblearn` (SMOTE)
* **Survival Analysis:** `lifelines`
* **Explainable AI:** `shap`
* **Visualization:** `matplotlib`, `seaborn`
* **Statistics:** `scipy`

## 👥 Team
* **Harsh Suresh Maurya** (Seat no.: 2502097)
* **Shubam Ashok Gupta** (Seat no.: 2502092)
* **Supervisor:** Namrata NAGWEKAR
* **Institution:** Department of Statistics, K.J. Somaiya College of Science and Commerce

---
> *Conducted between 20th October, 2025 – 10th January, 2026*
