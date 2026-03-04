# ⚡ EV Battery Quality Control Analysis
### End-to-End Business Analytics Project | Python · Pandas · Scikit-learn

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Project Overview

A complete business analytics case study on a simulated EV battery manufacturing dataset (20,000 cells). This project mirrors the workflow of a real-world BA/Data Analyst: framing the business problem, cleaning data, identifying root causes, quantifying financial impact, and delivering actionable recommendations — topped off with a predictive ML model.

**Dataset:** [EV Battery QC Data 2026 — Kaggle](https://www.kaggle.com)  
**Domain:** Electric Vehicle Manufacturing / Quality Control  
**Scope:** 20,000 battery cells | 3 suppliers | 3 production lines | 3 shifts | 14 features

---

## 🎯 Business Problem

> An EV battery manufacturer is experiencing a **15.4% scrap rate**, costing an estimated **$460K+ annually**. Leadership needs to understand *why* cells are being scrapped and *where* to intervene.

**Questions this analysis answers:**
1. Which supplier is driving the most defects and scrap?
2. Which production line and shift underperform on quality?
3. What physical measurements best predict a cell becoming scrap?
4. Can we build a model to flag at-risk cells before final QC?

---

## 🔍 Key Findings

| Finding | Detail |
|---|---|
| **Overall Scrap Rate** | 15.4% — 3,073 of 20,000 cells scrapped |
| **#1 Defect** | High Internal Resistance (14.2% of all cells) |
| **Worst Supplier** | VoltIndustries — 42.3% defect rate (4× higher than peers) |
| **Worst Shift** | Evening — 16.1% scrap rate vs 14.6% Night shift |
| **Strongest Predictor** | Internal Resistance + Retention (top ML features) |
| **Annual Scrap Cost** | ~$461,000 (estimated at $12.50/cell) |

---

## 💡 Business Recommendations

1. **Supplier Audit — VoltIndustries**: Initiate a formal quality review or begin sourcing transition. If VoltIndustries matched LithioMat's scrap rate, the company could save ~$27K/year on this supplier alone.

2. **Inline Resistance Monitoring**: High Internal Resistance drives the majority of defects. Implementing mid-process resistance checks can catch failing cells earlier, reducing downstream waste.

3. **Evening Shift Investigation**: The evening shift shows a consistently elevated scrap rate. A targeted process/staffing review is warranted.

4. **Deploy Predictive Classifier**: The Random Forest model achieves ~78% recall on scrap detection using production-time features — enabling real-time flagging before final QC.

---

## 📊 Analysis Sections

```
1. Setup & Data Loading
2. Data Quality & Cleaning        ← Missing value imputation, feature engineering
3. Exploratory Data Analysis      ← Grade distribution, defect breakdown
4. Supplier Quality Analysis      ← Scrap rate, defect rate, resistance by supplier
5. Production Line & Shift        ← Line/shift heatmaps, performance comparison
6. Scrap Cost Analysis            ← Financial impact quantification
7. Feature Correlation            ← Key predictors of scrap
8. Predictive Model               ← Random Forest classifier, feature importance
9. Executive Summary              ← Business recommendations
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| `pandas` | Data manipulation & aggregation |
| `matplotlib` / `seaborn` | Visualisation |
| `scikit-learn` | Random Forest model, evaluation metrics |
| `numpy` | Numerical operations |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/ev-battery-qc-analysis.git
cd ev-battery-qc-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Place the dataset in the project root
# (download from Kaggle: ev_battery_qc_data_2026_kaggle.csv)

# Launch the notebook
jupyter notebook EV_Battery_QC_Analysis.ipynb
```

---

## 📁 Project Structure

```
ev-battery-qc-analysis/
│
├── EV_Battery_QC_Analysis.ipynb   # Main analysis notebook
├── README.md                       # This file
└── ev_battery_qc_data_2026_kaggle.csv  # Dataset (add after cloning)
```

---

## 📈 Sample Visualisations

The notebook produces 10 publication-quality charts including:
- QC grade distribution (bar + pie)
- Defect type frequency (horizontal bar)
- Supplier quality scorecard (3-panel comparison)
- Defect type by supplier breakdown
- Production line × shift heatmap
- Annual scrap cost by supplier
- Feature correlation heatmap
- Key metric distributions by QC grade
- Random Forest confusion matrix + feature importances

---

## 👤 About

Built as a portfolio project demonstrating end-to-end business analytics skills:
- Problem framing & hypothesis formulation
- Data cleaning & feature engineering
- Exploratory analysis & root cause identification
- Financial impact quantification
- Predictive modelling (classification)
- Executive-level communication of findings

---

*Dataset is publicly available on Kaggle. All cost estimates are illustrative.*
