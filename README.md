# 🛍️ Retail Sales & Profit Analysis – End-to-End Analytics Project

This repository contains a complete, beginner-friendly, cloud-integrated analytics workflow built around a retail dataset. It demonstrates data cleaning, exploratory analysis, cloud SQL integration, and interactive dashboarding using Python, BigQuery, and Power BI.

---

## 🎯 Objective

Analyze retail sales data to uncover trends, regional performance, and profit drivers. The project simulates a real-world analytics pipeline using:

- Python for data cleaning, analysis, and visualization
- Google BigQuery for cloud-hosted SQL queries
- Power BI for interactive dashboarding

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `1st-proj-retail-eda-sql-pow-bi.ipynb` | Main Jupyter notebook: loads raw data, cleans it, performs EDA, visualizes trends, and uploads cleaned CSV to BigQuery |
| `superstore_cleaned.csv` | Cleaned dataset generated from the notebook, ready for SQL and dashboarding |
| `Sample - Superstore.csv` | Original dataset downloaded from Kaggle |
| `st-proj-retail-eda-sql-pow-bi-1022115cf4e9.json` | Google Cloud service account key for BigQuery authentication (⚠️ should be excluded from public repos) |
| `superstore_sales_visualization.pbix` | Power BI file connected to BigQuery, containing visuals and KPIs |
| `Dashboard-superstore_sales.pdf` | Exported PDF of the Power BI dashboard for quick reference or sharing |

---

## 🔧 Tools & Technologies

- **Python**: pandas, matplotlib, seaborn, google-cloud-bigquery
- **Google Cloud BigQuery**: cloud-hosted SQL queries
- **Power BI**: interactive dashboard with slicers, KPIs, and visuals
- **Kaggle**: dataset source

---

## 🚀 Workflow Summary

1. **Data Acquisition**  
   Downloaded `Sample - Superstore.csv` from Kaggle and saved as `superstore_cleaned.csv` after cleaning.

2. **Data Cleaning & EDA (Python)**  
   - Removed inconsistencies  
   - Converted date formats  
   - Created new columns (`Month`, `Revenue`)  
   - Visualized trends (sales by region, profit vs discount, top products)

3. **Cloud Integration (BigQuery)**  
   - Uploaded cleaned CSV to BigQuery table `sales` in dataset `retail_data`  
   - Ran SQL queries for monthly revenue, top products, and regional performance

4. **Dashboarding (Power BI)**  
   - Connected Power BI to BigQuery  
   - Built visuals: bar charts, line charts, pie charts, slicers  
   - Exported dashboard as PDF

---

## 📊 Key Insights

- Regional sales distribution and profit margins
- Monthly revenue trends
- Top-performing products by sales
- Impact of discounting on profitability


---

## 📌 Author

**Vijayan Shinde (VJ)**  
MSc Data Analytics & Decision Science – RWTH Aachen  
Cloud-integrated analytics and Machine learning enthusiast | Python, SQL, Power BI | Workflow automation & reproducibility

