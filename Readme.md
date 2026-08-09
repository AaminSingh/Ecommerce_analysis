# Ecommerce Sales Dashboard & Analysis
live :https://aaminsingh-ecommerce-analysis-ecommerce-dashboard-clp0pg.streamlit.app/

This project is a complete end-to-end ecommerce analytics solution built in Python. It combines data cleaning, exploratory analysis, visualizations, and an interactive dashboard to help understand sales performance and customer behavior.

The repository contains:
- an interactive Streamlit dashboard for exploring ecommerce data,
- a Jupyter notebook with step-by-step analysis and visualizations,
- cleaned and summarized CSV outputs for further analysis.

## Project Overview

The goal of this project is to analyze ecommerce transaction data and present meaningful business insights through a dashboard. It covers:
- revenue analysis,
- product performance,
- country-wise sales,
- order value distribution,
- customer spending patterns,
- simple customer spend prediction using machine learning.

## Features

### Dashboard capabilities
- Interactive filters for country and date range
- KPI cards for total revenue, total orders, total customers, and average order value
- Monthly revenue trend visualization
- Top countries by revenue
- Top products by revenue
- Order value distribution chart
- Revenue by day of week and hour of day
- Top customers table
- Customer spend prediction tool using a linear regression model

### Analysis notebook
The notebook file includes:
- data loading and cleaning,
- missing value handling,
- transaction filtering,
- feature engineering such as year/month/day/hour extraction,
- summary statistics,
- charts and plots,
- machine learning model training and evaluation.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit

## Project Structure

- ecommerce_dashboard.py - main Streamlit dashboard application
- ecom_analysis.ipynb - notebook for data analysis and visualization
- data.csv - raw ecommerce transaction dataset
- Cleaned _ecommerce_data.csv - cleaned transaction data exported from the notebook
- customer_summary.csv - customer-level summary report
- country_revenue.csv - country-wise revenue summary
- requirements.txt - Python dependencies

## Installation

1. Clone the repository.
2. Navigate to the project folder.
3. Install the required packages:

```bash
pip install -r requirements.txt
```

## Run the Dashboard

From the project folder, run:

```bash
streamlit run ecommerce_dashboard.py
```

Then open the local Streamlit URL in your browser.

## Live Demo

The dashboard is also deployed online here:

https://aaminsingh-ecommerce-analysis-ecommerce-dashboard-clp0pg.streamlit.app/

## Example Insights

This project can help answer questions such as:
- Which countries generate the most revenue?
- Which products contribute the most sales?
- What is the revenue trend over time?
- Which customers spend the most?
- How can a new customer’s spend be estimated from order behavior?

## Notes

The dataset used in this project is a sample ecommerce transaction dataset and is suitable for learning data analysis, visualization, and basic predictive modeling.
