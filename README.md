# Retail Performance Analysis

## 📊 Project Overview

This project analyzes retail sales data from Favorita, a supermarket chain in Ecuador, with the goal of identifying sales trends, product performance, store-level differences, promotional patterns, and the relationship between sales and holidays and events.

The analysis focuses on transforming raw retail data into actionable business insights through exploratory data analysis and data visualization.

## 🎯 Business Questions

- How have total sales evolved over time?
- Which product families generate the highest sales?
- Which cities and stores have the highest sales?
- How does sales performance vary across store types?
- Is there an association between promotions and sales?
- How do sales behave on holidays and special events?
- Which stores show the highest sales variability?

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## 📂 Datasets

The analysis uses several datasets from the Favorita Store Sales dataset:

- `train.csv` — Daily sales by store and product family.
- `stores.csv` — Store information, including city, state, type, and cluster.
- `holidays_events.csv` — Holidays and events in Ecuador.

## 📥 Data Source

The dataset used in this project comes from the Store Sales - Time Series Forecasting competition on Kaggle, provided by Corporación Favorita.

The original dataset includes historical sales data and supporting information such as store metadata, holidays and events, oil prices, and transactions.

train.csv is not included in this repository due to GitHub’s file size limitations. 
Kaggle: ryanholbrook/exercise-trend

## 🔎 Analysis

The project includes:

- Initial data exploration
- Data quality assessment
- Data type preparation
- Time-series sales analysis
- 30-day rolling average
- Product family performance
- City-level sales analysis
- Store-level performance
- Promotion and sales analysis
- Store type comparison
- Sales variability by store
- Holiday and event analysis

## 💡 Key Findings

- Total sales show an overall increasing trend throughout the analyzed period.
- `GROCERY I` and `BEVERAGES` are among the product families with the highest sales volume.
- Quito records the highest accumulated sales among the analyzed cities, followed by Guayaquil.
- Store performance varies considerably across locations and store types.
- Stores 44, 45, and 47 show particularly high sales variability.
- Higher numbers of products on promotion are associated with higher average sales; however, this analysis does not establish a causal relationship.
- Average sales differ across holiday and event categories.

## 📌 Business Recommendations

Based on the exploratory analysis:

1. Investigate high-variability stores to better understand fluctuations in demand.
2. Prioritize high-performing product families when evaluating inventory and commercial strategies.
3. Evaluate promotional strategies using additional analysis to determine their effectiveness.
4. Consider seasonality and special events when planning sales and inventory.
5. Investigate geographic differences in store performance to identify potential opportunities.

## 📓 Notebook

The complete analysis, visualizations, findings, and conclusions are available in:

`retail_sales_analysis.ipynb`

## 👤 Author

**Demian Elizalde**

Data Analyst Portfolio Project
