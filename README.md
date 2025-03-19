# Walmart Sales Forecasting

##  Project Overview
This project aims to forecast sales for Walmart stores using machine learning techniques. The goal is to provide valuable insights for inventory management and demand forecasting, helping stores optimize operations and mitigate financial risks.

##  Problem Statement
Walmart is facing inventory management challenges due to fluctuating demand. The objective is to develop predictive models that forecast weekly sales for each store, allowing for better planning and decision-making.

##  Objectives
- Analyze historical sales data to identify key trends.
- Build machine learning models to predict sales for the next 12 weeks.
- Provide actionable insights to improve store operations.

##  Dataset Description
The dataset consists of **6435 rows and 8 columns**, with the following features:
- **Store**: Store number  
- **Date**: Weekly sales date  
- **Weekly_Sales**: Total sales for the store  
- **Holiday_Flag**: Indicates if the week includes a holiday  
- **Temperature**: Recorded temperature on the sales day  
- **Fuel_Price**: Fuel cost in the region  
- **CPI**: Consumer Price Index  
- **Unemployment**: Unemployment rate  

##  Data Preprocessing
1. Data loading and inspection
2. Conversion of the `Date` column to datetime format
3. Handling missing values
4. Visualization of sales trends over time

##  Machine Learning Approach
Two models were used for forecasting:
- **ARIMA (Auto-Regressive Integrated Moving Average)**: Effective for univariate time series forecasting.
- **Random Forest**: Helps capture complex patterns in historical sales data.

### Model Evaluation Metrics:
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

**Findings:**  
- ARIMA performed better for time-series forecasting.
- External factors (holidays, fuel prices) significantly impact sales.

##  Future Enhancements
To improve forecasting accuracy, we can integrate:
- Promotional campaign data
- Competitor pricing strategies
- Additional economic indicators

##  Conclusion
This project successfully forecasts Walmart sales and provides key insights for improving inventory management. The models can assist in strategic planning, reducing losses, and improving efficiency.

##  References
1. *Sales Forecasting using Random Forest Algorithm* - S. Senthilkumar, R. Srinath (2020)  
2. *Incorporating External Factors into Sales Forecasting Models: A Systematic Review* - A. Kumar et al. (2022)
