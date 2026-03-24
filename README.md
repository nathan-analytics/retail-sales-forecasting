# Retail Sales Forecasting & Trend Analysis

End-to-end retail sales forecasting project using Python and Power BI to analyze trends, identify seasonality, and predict future performance.

## Dashboard Preview
<img width="1155" height="649" alt="forecast-overview" src="https://github.com/user-attachments/assets/2d8298a0-8586-4281-8460-e0ddf273ea0b" />
<img width="1137" height="652" alt="sales-trends-and-performance-drivers" src="https://github.com/user-attachments/assets/10761171-845a-4ec1-b47c-aee663f0aabc" />

---

## Project Overview
This project analyzes historical retail sales data to identify trends, evaluate seasonality, and forecast future sales performance. The goal was to simulate a real-world analytics workflow by transforming cleaned transactional data into a monthly time series, building a forecasting model in Python, and presenting insights through a Power BI dashboard.

The analysis focused on understanding historical sales patterns, smoothing short-term fluctuations with rolling averages, and generating a 6-month sales forecast to support short-term planning and decision-making.

## Tools Used
- Python
- Pandas
- Prophet
- Power BI

---

## Project Structure
```text
retail-sales-forecasting/
│
├── 01_data_source/
│   └── superstore_cleaned_orders.csv
│
├── 02_python/
│   ├── 01_validation.ipynb
│   └── 02_time_series.ipynb
│
├── 03_analysis_output/
│   ├── monthly_sales_timeseries.csv
│   ├── sales_forecast.csv
│   └── actual_vs_forecast_chart_data.csv
│
├── 04_forecasting/
│   └── 01_forecast_model.ipynb
│
├── 05_powerbi/
│   └── sales-forecast-analysis.pbix
│
├── 06_screenshots/
│
└── README.md
```

---

## Data Preparation
The project began with a cleaned retail orders dataset prepared in a previous analysis. For this project, the dataset was validated in Python to confirm date formatting, numeric fields, missing values, duplicates, and overall readiness for time series analysis.

The transactional data was then aggregated to the monthly level to create a time series dataset containing:
 - total sales
 - total profit
 - 3-month rolling sales trend
 - 3-month rolling profit trend

Intermediate datasets were exported to support transparency and reproducibility of the analysis pipeline.

---

## Forecasting Approach
A forecasting model was built in Python using Prophet. Historical monthly sales were reformatted into the required time series structure and used to generate a 6-month sales forecast.

To support dashboard development, forecast outputs were exported into separate analysis files, including:
 - monthly sales time series data
 - detailed forecast output
 - a combined actual vs forecast dataset for Power BI visualization

---

## Dashboard Overview

### Page 1: Sales Forecast & Performance Overview

This page highlights:
 - total historical sales
 - projected sales for the next 6 months
 - minimum and maximum expected sales
 - actual vs forecasted sales trend
 - high-level forecast insights

### Page 2: Sales Trends and Performance Drivers

This page highlights:
 - monthly sales trend
 - 3-month rolling sales trend
 - monthly profit trend
 - key insights on seasonality, growth phases, and profit volatility

---

## Key Insights
 - Sales show a consistent upward trend, indicating sustained business growth over time.
 - Forecasted sales point to continued short-term growth within a stable range.
 - The narrow forecast range suggests predictable sales patterns with moderate variability.
 - Sales exhibit seasonal fluctuations, with recurring demand spikes across the observed period.
 - The rolling 3-month trend highlights sustained growth phases followed by short-term corrections.
 - Profit trends generally follow revenue but show increased volatility, suggesting inconsistent margins across periods.

---

## Business Impact
This analysis demonstrates how historical sales data can be used not only to understand past performance, but also to support future planning. The forecast suggests the business is positioned for steady short-term revenue growth, while the historical trend analysis highlights recurring demand patterns and profitability fluctuations that may influence planning decisions.

## Skills Demonstrated
 - Data validation and preparation in Python
 - Time series transformation and trend analysis
 - Sales forecasting with Prophet
 - Dashboard design and business communication in Power BI
 - Translating analytical output into business insights

---

## How to Use
1. Review the Python notebooks for validation, time series preparation, and forecasting.
2. Open the Power BI file to explore the final dashboard.
3. Reference the exported CSV files for supporting analysis outputs.

---

## About This Project
This project was built as part of a data analytics portfolio focused on demonstrating practical business analysis, forecasting, and dashboard development skills for junior data analyst roles.
