# Superstore Sales Analysis

Exploratory Data Analysis on a retail store chain dataset using Python.

Dataset url : https://www.kaggle.com/datasets/rouzbeh/stores-dataset

## Dataset
- **Source:** Stores dataset (Kaggle)
- **Records:** 118 stores, 7 features
- **Features:** Store Number, Area, Property type, Store type, Old/New, Checkout counters, Revenue

## Questions Explored

| # | Question |
|---|---|
| Q1 | Which type of store generates the highest revenue? |
| Q2 | Which are the top 10 lowest revenue stores? |
| Q3 | What is the revenue split between old and new stores? |
| Q4 | Is revenue affected by store area? |
| Q5 | What is the correlation between Revenue, Area, and Checkout counters? |
| Q6 | What is the distribution of store revenues? |
| Q7 | How does revenue vary across store types and are there outliers? |

## Key Findings
- **Hyper stores** generate the highest revenue at ₹1.25B, followed by Extra (₹0.88B) and Express (₹0.58B)
- **New stores dominate** with 93.6% of total revenue — old stores contribute only 6.4%
- **Checkout Number** is the strongest revenue driver (correlation = 0.78)
- **Store area** moderately affects revenue (correlation = 0.68)
- **Revenue is right-skewed** — most stores earn below ₹0.02B while a few high performers pull the average up
- **Store 8** is a major outlier — earns significantly above all other Hyper stores
- **Bottom 10 stores** (59, 102, 12, 98 etc.) earn below ₹0.005B and need immediate review

## Tools Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
