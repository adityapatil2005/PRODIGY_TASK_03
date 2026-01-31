# 🏦 PRODIGY_DS_03 – Bank Marketing Decision Tree

> A Machine Learning project that predicts whether a customer will subscribe to a **Bank Term Deposit** using a **Decision Tree Classifier**.

---

## 📌 Project Overview
This project demonstrates a complete **end-to-end ML workflow** including:
- Exploratory Data Analysis (EDA)
- Data Preprocessing & Feature Engineering
- Model Training
- Performance Evaluation

**Goal:** Classify customers as *Yes* or *No* for term-deposit subscription using the **UCI Bank Marketing Dataset**.

---

## 📊 Dataset Summary
| Attribute | Value |
|---------|--------|
| Source | UCI Machine Learning Repository |
| Records | 45,211 Clients |
| Features | 16 Inputs + 1 Target |
| Target | `y` (Yes / No) |
| Class Distribution | 11.7% Yes • 88.3% No |

**Key Variables:** `age`, `job`, `education`, `duration`, `campaign`, `pdays`, `poutcome`

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **Visualization:** Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook

## viualization 
<img width="1449" height="687" alt="Screenshot 2026-01-31 214036" src="https://github.com/user-attachments/assets/c787a44e-37e8-4fcc-a03e-3c5f53206a5c" />


---

## ⚙️ Methodology
- Data Cleaning & Visualization  
- Label Encoding for Categorical Features  
- Outlier Removal using **IQR** (`duration`)  
- Train/Test Split – **75 / 25**  
- Decision Tree Classifier (**Gini Impurity**)  

---

## 📈 Model Performance
| Metric | Score |
|--------|-------|
| **Accuracy** | **89.2%** |
| **ROC-AUC** | **0.91** |
| **Precision (Yes)** | **0.58** |
| **Recall (Yes)** | **0.52** |

---

## 🔍 Feature Insights
- **pdays** – Recency of previous contact  
- **duration** – Length of last call (strongest predictor)  
- **age** – 30–50 age group most responsive  
- **poutcome** – Previous campaign success  
- **campaign** – Best results with 1–3 contacts  

---

## ▶️ Getting Started

### 1. Install Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
git clonehttps://github.com/adityapatil2005/PRODIGY_TASK_03/tree/main
cd PRODIGY_DS_03
