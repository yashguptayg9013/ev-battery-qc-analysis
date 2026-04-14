# 🔋 EV Battery Quality Control Analysis

A statistical quality control (SQC) analysis of electric vehicle battery manufacturing data. This project identifies defect patterns, failure rates, and process inefficiencies across production batches using Python-based statistical methods.

---

## 📌 Business Question

> *Where are quality failures occurring in the EV battery production process, and what data-driven interventions can reduce defect rates and improve manufacturing consistency?*

---

## 📊 Analysis Coverage

- **Defect Rate Analysis** — Batch-level defect frequency and trend over production runs
- **Statistical Process Control (SPC)** — Control charts (X-bar, R-chart) to flag out-of-control processes
- **Outlier Detection** — Z-score and IQR-based methods to identify anomalous battery units
- **Failure Mode Breakdown** — Category-level analysis of defect types (capacity, resistance, cycle life)
- **Correlation Analysis** — Relationship between production variables (temperature, charge cycles) and failure rates
- **Recommendations** — Data-driven suggestions for process improvement

---

## 🔍 Key Findings

- Certain **production batches** showed defect rates 2–3x above the control limit, indicating process drift
- **Temperature variance** during manufacturing was the strongest predictor of battery capacity defects
- SPC charts identified **3 specific production periods** where the process went out of control
- Implementing tighter thermal controls could potentially reduce defect rates by an estimated 20–25%

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 📁 Repository Structure

```
ev-battery-qc-analysis/
│
├── data/
│   └── ev_battery_qc_data.csv         # Manufacturing QC dataset
├── ev_battery_qc_analysis.ipynb       # Main analysis notebook
├── figures/                           # Output visualisations
└── README.md
```

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/yashguptayg9013/ev-battery-qc-analysis.git
cd ev-battery-qc-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter scipy

# Launch the notebook
jupyter notebook ev_battery_qc_analysis.ipynb
```

---

## 💡 Business Impact

This analysis demonstrates how statistical process control techniques — traditionally used in automotive manufacturing — can be applied to EV battery production to reduce waste, improve yield, and lower cost-per-unit. The methodology is transferable to any high-volume precision manufacturing environment.

---

## 📬 Author

**Yash Gupta** — MSc Business Analytics, Dublin Business School
[LinkedIn](https://www.linkedin.com/in/yashguptayg9013/) · [GitHub](https://github.com/yashguptayg9013)
