# Sales & Profitability Forecasting

Forecasted sales and profit trends using Python to support revenue planning, margin stability, and business decision-making.

## Project Summary

Analyzed historical retail data and built a time series forecasting model to predict sales and profit performance over the next 6 months.

Key findings:
- Sales show consistent upward growth with clear seasonal demand patterns
- Forecast indicates stable short-term revenue growth within a predictable range
- Profit follows similar trends but is more volatile, highlighting margin instability
- Peak demand periods can be anticipated for better planning

Business impact:
- Enables proactive inventory and staffing decisions
- Helps align marketing with high-demand periods
- Supports forward-looking revenue planning
- Highlights the need to monitor and manage margin stability

## Dashboard Highlight

Sales show steady upward growth over time, indicating consistent demand and a stable revenue trajectory.

![Forecast Overview](./06_screenshots/forecast-overview.png)  

Sales and profit move together over time, but profit is more volatile, indicating that future performance depends on maintaining margin stability.

![Sales Trends and Performance Drivers](./06_screenshots/sales-trends-and-performance-drivers.png)

## Case Study

[Sales & Profitability Forecasting Case Study](case_study.pdf)

## Key Insights

- Sales trend upward over time with consistent growth patterns
- Clear seasonality with recurring demand spikes during peak periods
- Forecast predicts stable revenue growth in the short term
- Profit is less stable than sales, indicating fluctuations in margin performance
- Rolling averages highlight sustained growth with short-term variability

## Project Overview

This project simulates a real-world forecasting workflow by transforming transactional data into a monthly time series and building predictive models for sales and profit.

Workflow:
- Cleaned and validated raw data using Python
- Aggregated transactional data into monthly metrics
- Built a forecasting model using Prophet
- Generated a 6-month forecast for sales performance
- Analyzed profit trends alongside revenue
- Visualized trends and predictions in Power BI

## Data Preparation

- Validated date formats, numeric fields, and missing values
- Aggregated transaction-level data to monthly level
- Created key metrics:
  - Total sales
  - Total profit
  - 3-month rolling sales trend
  - 3-month rolling profit trend

## Forecasting Approach

- Built a time series forecasting model using Prophet
- Generated a 6-month forward-looking sales prediction
- Compared historical trends with forecasted performance
- Evaluated alignment between actual and predicted values

## Dashboard Features

- Historical vs forecasted sales comparison
- Actual vs predicted trend visualization
- Monthly sales and profit trends
- Rolling average trend analysis
- Seasonality insights and performance patterns

## Business Recommendations

- Use forecasts to guide inventory and staffing decisions  
→ Expected Impact: Reduce stockouts and improve operational planning  

- Align marketing campaigns with seasonal demand peaks  
→ Expected Impact: Increase campaign effectiveness and revenue  

- Monitor profit volatility to improve margin consistency  
→ Expected Impact: Reduce margin fluctuations and improve profitability  

- Continuously retrain forecasting models with new data  
→ Expected Impact: Maintain forecast accuracy and improve decision-making  

## Tools Used

- Python (Pandas, Prophet)
- Power BI

## Dataset

Monthly aggregated retail sales data derived from transactional orders

## Project Structure

sales-and-profitability-forecasting/  
├── 01_data_source/  
├── 02_python/  
├── 03_analysis_output/  
├── 04_forecasting/  
├── 05_powerbi/  
├── 06_screenshots/  
├── case_study.pdf  
└── README.md
