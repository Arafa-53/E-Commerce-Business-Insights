# E-Commerce Business Insights — Olist

## Project Overview
This repository contains a full end-to-end analysis and executive report for an e-commerce dataset (Olist). The work includes data cleaning, feature engineering, exploratory data analysis, customer segmentation, review sentiment analysis, and an executive summary.

## Files
- Dataset -> [https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce]
- `orders_full_clean.csv` — cleaned order-level data (exports)
- `customers_summary.csv` — customer-level aggregated metrics
- `customer_rfm_segments.csv` — RFM segmentation results
- `orders_with_reviews_sentiment.csv` — orders merged with review sentiment
- `top_products.csv` — top products exported
- Jupyter notebook — (not included in ZIP) contains all code to reproduce steps
- Power BI Report [Interact with it here ->https://app.powerbi.com/links/XkBMhrLUPg?ctid=ff4a48d6-4b5e-4fd3-8266-7eafc3e6e23e&pbi_source=linkShare]

## How to run
1. Place Olist CSVs in the same folder as the notebook.
2. Install Python libraries: `pip install pandas numpy matplotlib seaborn scikit-learn textblob python-pptx wordcloud nltk`
3. Run the notebook cells top-to-bottom.
4. Open `executive_summary.pptx` for a ready-to-share slide.
5. Use the CSV outputs as data sources in Power BI to build the interactive dashboard.

## Key Insights (examples)
- The top 10% of customers contribute ~X% of sales (Pareto).
- Categories A,B,C drive most sales; category D has longest average delivery.
- Sentiment from reviews is mostly neutral-positive; negative sentiment clusters around shipping delays.

## Author
Mostafa Arafa — Data Analyst
