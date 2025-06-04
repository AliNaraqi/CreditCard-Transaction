💳 Credit Card Transactions Analysis

This project analyzes real-world credit card transaction data to uncover trends, identify potential fraud, and build a reproducible data pipeline. It includes data cleaning, time series analysis, and anomaly detection using unsupervised machine learning.

---

📂 Project Structure

```
credit-card-transactions-analysis/
├── data/                     # Raw dataset (CSV)
├── notebooks/               # Jupyter notebooks
│   └── exploratory_analysis.ipynb
├── src/                     # Python scripts (modular functions)
│   ├── data_cleaning.py
│   ├── visualization.py
│   └── fraud_detection.py (optional)
├── outputs/                 # Plots, cleaned data
├── requirements.txt         # Python dependencies
└── README.md                # Project overview
```

---

📊 Features Implemented

 ✅ Data Cleaning**

  Removed duplicates, filled missing values
  Formatted `trans_date_trans_time` as datetime

 ✅ Exploratory Data Analysis (EDA)

Distribution of transaction amounts
Top categories and merchants

✅ Time Series Analysis

Daily and monthly spending trends

✅ Fraud Detection**

Rule-based: flag transactions > 99th percentile
ML-based: Isolation Forest to detect anomalies

---

 🚀 Getting Started

1. Clone the repo**

```bash
git clone https://github.com/yourusername/credit-card-transactions-analysis.git
cd credit-card-transactions-analysis
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run analysis
   Open the Jupyter notebook:

```bash
jupyter notebook notebooks/exploratory_analysis.ipynb
```

---

📈 Sample Visuals *(optional screenshots)

Distribution of amounts
Time-based trends
Fraud detection breakdowns

---

 🛠 Built With

Python, pandas, seaborn, matplotlib
scikit-learn (for anomaly detection)
Jupyter Notebook

---


📄 License

MIT License
