# Churn Analysis and Customer Intelligence

Customer churn analysis project built with Python, pandas, SQLite, Matplotlib, and Seaborn.

## Project overview

This analysis imports customer, subscription, and support data from SQLite, cleans and joins the source tables, engineers churn and tenure features, calculates business KPIs, and visualizes churn patterns.

## Included files

- `churn_analysis.ipynb` - complete, step-by-step analysis notebook with tables and charts.
- `customer_churn.db` - SQLite database used by the notebook.
- `customer_churn_data_raw.xlsx` - original workbook used to recreate the database.
- `Data Analytics Project -Churn Analysis Report.pdf` - report and visual summary of the project.

## Analysis workflow

1. Import the SQLite tables and inspect their schemas.
2. Clean customer, subscription, and support data.
3. Merge the datasets and remove duplicate support records.
4. Engineer churn, tenure, complaint, escalation, and churn-risk features.
5. Calculate churn rate, retention rate, ARPU, revenue at risk, and related KPIs.
6. Explore churn trends by month and plan type with visualizations and pivot tables.

## Visual results

The notebook includes the project charts inline, including:

- Monthly churn trend
- Churn rate by plan type
- Churn and retention KPIs
- Customer churn-risk analysis
- Plan-level summary tables

For a presentation-ready visual summary, open [Data Analytics Project -Churn Analysis Report.pdf](Data%20Analytics%20Project%20-Churn%20Analysis%20Report.pdf). GitHub also renders the notebook outputs directly in the notebook view.

## Run locally

```bash
pip install -r requirements.txt
jupyter notebook churn_analysis.ipynb
```

The notebook expects the database, Excel workbook, and notebook to remain in the same directory.

## Author

Ashish Kumar Yadav