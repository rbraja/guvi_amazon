# 🛒 Amazon India Analytics Dashboard (2015–2025)

## 📊 Overview
This Streamlit-based analytics dashboard provides deep insights into **Amazon India sales data** from 2015–2025.  
It includes automated data cleaning, exploratory data analysis (EDA), SQL-based querying, and visualization dashboards — all in one interactive interface.

---

## 🧩 Project Structure

```
AMAZON_DASHBOARD/
│
├── app.py                         # Main Streamlit entry point
├── requirements.txt               # Python dependencies
│
├── pages/                         # Modular pages for navigation
│   ├── 01_data_cleaning_summary.py
│   ├── 02_EDA.py
│   ├── 03_sql.py
│   └── __init__.py
│
├── utils/                         # Helper functions
│   ├── data_loader.py             # Load & clean CSV (only once)
│   ├── data_cleaning.py           # Data preprocessing logic
│   ├── db_utils.py                # Database connection utilities
│   └── __init__.py
│
├── data/
│   ├── raw/                       # Raw input files (e.g. CSV, DB)
│   └── clean/                     # Cleaned and merged datasets
│       └── amazon_india_clean.csv
│
└── amazon_analytics.db            # SQLite database (optional)
```


## 📈 Features

✅ Automated data cleaning (runs only once per session)  
✅ EDA with 20+ chart types (bar, scatter, line, box, heatmap, etc.)  
✅ SQL query interface with live result preview  
✅ Modular multi-page layout  
✅ Responsive & interactive visuals (using Plotly + Streamlit)  

---

## 🧠 Tech Stack

| Component | Technology |
|------------|-------------|
| UI & Framework | Streamlit |
| Data Handling | Pandas, NumPy |
| Visualization | Seaborn, Matplotlib |
| Database | SQLite |
| Language | Python 3.12+ |

---
