# Retail Sales Forecasting & Trend Analysis  
Python + Power BI  

Built a time series forecasting model to analyze sales trends, identify seasonality, and predict future performance.

---

## Dashboard Preview  
<img width="1155" height="649" alt="forecast-overview" src="https://github.com/user-attachments/assets/2d8298a0-8586-4281-8460-e0ddf273ea0b" />
<img width="1137" height="652" alt="sales-trends-and-performance-drivers" src="https://github.com/user-attachments/assets/10761171-845a-4ec1-b47c-aee663f0aabc" />

---

## 📄 Case Study  
[Retail Sales Forecasting.pdf](https://github.com/user-attachments/files/26418328/Retail.Sales.Forecasting.pdf)

---

## Key Insights  
• Sales show a consistent upward trend over time  
• Forecast predicts continued short-term growth within a stable range  
• Sales exhibit clear seasonal patterns with recurring demand spikes  
• Profit trends follow revenue but show higher volatility  
• Rolling averages highlight sustained growth periods and short-term fluctuations  

---

## Business Questions  
• What trends and patterns exist in historical sales data?  
• Is there evidence of seasonality in sales performance?  
• What are the expected sales for the next 6 months?  
• How stable or volatile are future sales projections?  

---

## Project Overview  
This project analyzes historical retail sales data to identify trends and forecast future performance.

The workflow simulates a real-world analytics process:
• Validated and prepared data using Python  
• Transformed transactional data into a monthly time series  
• Built a forecasting model using Prophet  
• Generated a 6-month sales forecast  
• Visualized results in Power BI  

The final output combines historical trends and forecasted data to support planning and decision-making.

---

## Tools Used  
Python (Pandas, Prophet), Power BI  

---

## Dataset  
Monthly aggregated retail sales data derived from transactional orders  

---

## Data Preparation  
• Validated date formats, numeric fields, and missing values  
• Aggregated transactional data to monthly level  
• Created key metrics:
  • total sales  
  • total profit  
  • 3-month rolling sales trend  
  • 3-month rolling profit trend  

---

## Forecasting Approach  
• Built a forecasting model using Prophet  
• Generated a 6-month forward-looking sales prediction  
• Created datasets for:
  • monthly sales time series  
  • forecast outputs  
  • actual vs forecast comparison  

---

## Dashboard Features  
• Total historical vs forecasted sales  
• Actual vs forecast trend comparison  
• Monthly sales and profit trends  
• Rolling average trend analysis  
• Seasonality and performance insights  

---

## Business Recommendations  
• Use forecasts to guide inventory and staffing decisions  
• Align marketing efforts with seasonal demand patterns  
• Monitor profit volatility to improve margin stability  
• Continuously update the model with new data for accuracy  

---

## Project Structure  
retail-sales-forecasting/  
├── 01_data_source/  
├── 02_python/  
├── 03_analysis_output/  
├── 04_forecasting/  
├── 05_powerbi/  
├── 06_screenshots/  
├── case_study.pdf  
└── README.md  
