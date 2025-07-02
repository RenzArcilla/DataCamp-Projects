# Walmart Sales Data Pipeline & Holiday Analysis

This project focuses on building a basic data pipeline to analyze the impact of public holidays on Walmart's sales. It combines transactional sales data from a PostgreSQL database with complementary store-level information stored in a Parquet file.

## 📊 Project Objectives

- Merge **grocery sales data** with **complementary data** (e.g., Weekly_Sales, CPI, unemployment).
- Clean and transform the merged dataset to create a `clean_data` DataFrame.
- Analyze **monthly sales** to understand seasonal and holiday impacts.
- Export both cleaned and aggregated data as CSV files for future use or visualization.

## 📁 Data Sources

1. **PostgreSQL Table: `grocery_sales`**
   - Weekly sales data for Walmart stores.

2. **Parquet File: `extra_data.parquet`**
   - Contains holiday flags, economic indicators, store details, and markdown info.

## 🧼 Output Datasets

- `clean_data.csv` – Merged and cleaned dataset with selected relevant columns.
- `agg_data.csv` – Aggregated sales grouped by month for trend analysis.

## Tools Used
- Python 3
- pandas
- PostgreSQL 


---

> 🔎 This project serves as a foundational exercise in data engineering, focusing on data integration, transformation, and exploratory analysis around key retail events.