# 📉 Integrated Customer Churn Prediction & Retention Analytics

> **A Hybrid Approach Using Ensemble Learning, Survival Analysis, and Voice of Customer (VoC) Insights**

[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Institution](https://img.shields.io/badge/K.J.%20Somaiya%20College-Statistics-red)](https://somaiya.edu)

---

## 📌 Project Overview

This research project develops a **comprehensive, explainable, and multi-dimensional churn prediction framework** for the telecom industry. The system answers three critical business questions:

| Question | Approach |
|---|---|
| **Who** will churn? | Ensemble Learning (Random Forest, XGBoost, AdaBoost, Stacking) |
| **When** will they churn? | Survival Analysis (Kaplan-Meier, Cox Proportional Hazards) |
| **Why** will they churn? | XAI (SHAP) + Voice of Customer (Survey Analysis) |

---

## 👥 Team

| Name | Seat No. |
|---|---|
| Harsh Suresh Maurya | 2502097 |
| Shubam Ashok Gupta | 2502092 |

**Supervisor:** Namrata Nagwekar  
**Department:** Statistics, K.J. Somaiya College of Science and Commerce  
**Duration:** October 2025 – January 2026

---

## 🗂️ Repository Structure

```
churn-prediction/
│
├── data/
│   ├── raw/                        # Original datasets (telecom customer logs)
│   └── processed/                  # Cleaned & feature-engineered data
│
├── notebooks/
│   ├── 01_EDA.ipynb                # Exploratory Data Analysis
│   ├── 02_Preprocessing.ipynb      # Data Cleaning & Feature Engineering
│   ├── 03_Ensemble_Models.ipynb    # Random Forest, XGBoost, AdaBoost, Stacking
│   ├── 04_Survival_Analysis.ipynb  # Kaplan-Meier & Cox PH Models
│   ├── 05_SHAP_Explainability.ipynb# SHAP Summary & Waterfall Plots
│   └── 06_VoC_Survey_Analysis.ipynb# Voice of Customer Survey Insights
│
├── reports/
│   └── Field_Project_Final_Report.docx
│
├── requirements.txt
└── README.md
```

> ⚠️ *Rename and organize your notebooks to match this structure before uploading.*

---

## 🧠 Methodology

### Phase 1 — Ensemble Learning (Classification)
- Trained **Random Forest**, **XGBoost**, **AdaBoost**, and a **Stacking Classifier**
- Compared accuracy, precision, recall, F1-score, and AUC-ROC
- Best result: XGBoost achieved **~79% accuracy**; Stacking models further improved performance

### Phase 2 — Survival Analysis (Time-to-Churn)
- Applied **Kaplan-Meier estimator** to visualize churn-free survival curves
- Built **Cox Proportional Hazards** model to identify risk factors over time

### Phase 3 — Voice of Customer (Survey Analysis)
- Collected primary survey data from telecom customers
- Performed statistical tests (chi-square, t-tests) to identify significant churn drivers

### Phase 4 — Explainability (SHAP + PCA)
- Used **SHAP (Shapley Additive Explanations)** to interpret ensemble model predictions
- Global feature importance + individual customer-level explanations

---

## 📊 Key Results

| Model | Accuracy |
|---|---|
| Random Forest | ~76% |
| XGBoost | ~79% |
| AdaBoost | ~75% |
| Stacking Classifier | Best overall |

- Top churn predictors identified via SHAP: contract type, tenure, monthly charges, tech support
- Survival curves showed significant churn risk within the **first 12 months**
- VoC analysis confirmed **network quality** and **customer service** as primary dissatisfaction drivers

---

## 🛠️ Tech Stack

```
Python 3.9+
├── pandas, numpy           — Data manipulation
├── matplotlib, seaborn     — Visualization
├── scikit-learn            — Ensemble models, preprocessing
├── xgboost                 — Gradient boosting
├── lifelines               — Survival analysis
├── shap                    — Model explainability
└── scipy, statsmodels      — Statistical testing
```

---

## ⚙️ Setup & Usage

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/churn-prediction.git
cd churn-prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run notebooks in order
Open Jupyter and run notebooks in the `notebooks/` folder sequentially (01 → 06).

```bash
jupyter notebook
```

---

## 📄 Report

The full academic report is available in [`reports/Field_Project_Final_Report.docx`](reports/Field_Project_Final_Report.docx).

---

## 📜 License

This project is submitted as an academic field project at K.J. Somaiya College of Science and Commerce, affiliated to the University of Mumbai. Code is made available under the [MIT License](LICENSE) for educational purposes.

---

## 🙏 Acknowledgements

We thank our supervisor **Namrata Nagwekar** for her invaluable guidance, and the **Department of Statistics** at K.J. Somaiya College for their support throughout this project.
