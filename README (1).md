# NeuralRetail Intelligence Platform

An end-to-end machine learning project analyzing customer behavior, sales trends, and business opportunities using the UCI Online Retail II dataset.

## Overview

This project covers the full analytics pipeline — from raw transaction data to actionable business insights — using classical machine learning and statistical techniques.

## Modules

| # | Module | Technique | Business Value |
|---|--------|-----------|-----------------|
| 1 | Data Cleaning | Pandas, Feature Engineering | Clean, ML-ready dataset |
| 2 | Exploratory Data Analysis | Matplotlib, Seaborn | Business KPI insights |
| 3 | RFM Segmentation | Quantile Scoring | Customer value ranking |
| 4 | KMeans Clustering | Scikit-learn | Automatic customer grouping |
| 5 | Demand Forecasting | Facebook Prophet | Statistical sales forecast |
| 6 | Churn Prediction | Logistic Regression, Random Forest, XGBoost | At-risk customer detection |
| 7 | Inventory Optimization | Reorder Point Formula | Stock planning |
| 8 | Cohort Analysis | Retention Heatmap | Customer loyalty tracking |
| 9 | Market Basket Analysis | Apriori Algorithm | Cross-sell opportunities |
| 10 | CLV Prediction | Formula + Segmentation | Future revenue per customer |

## Dataset

[UCI Online Retail II Dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii) — transactional data from a UK-based online retailer (2009–2011), containing 1M+ invoice line items.

## Tech Stack

- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Prophet, mlxtend
- **Environment:** Jupyter Notebook / Kaggle

## Key Insights

- Segmented customers into value tiers using RFM + KMeans, enabling targeted retention campaigns
- Built churn prediction models evaluated on precision, recall, F1-score, and ROC-AUC
- Identified frequently co-purchased product combinations using Apriori (support, confidence, lift)
- Forecasted demand trends using Prophet to support inventory planning
- Estimated Customer Lifetime Value (CLV) to prioritize high-value customer segments

## How to Run

1. Clone the repository
```bash
git clone https://github.com/<your-username>/neuralretail-intelligence-platform.git
cd neuralretail-intelligence-platform
```

2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost prophet mlxtend
```

3. Open the notebook
```bash
jupyter notebook neuralretail-notebook.ipynb
```

## Author

**Sneha Gupta**
B.Tech CSE (Data Science) — Hindustan College of Science and Technology
