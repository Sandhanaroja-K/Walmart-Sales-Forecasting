# Capstone Project - Walmart Sales Forecasting

### Author: Sandhana Roja K

## Table of Contents
1. [Problem Statement](#problem-statement)
2. [Project Objective](#project-objective)
3. [Data Description](#data-description)
4. [Data Pre-processing Steps and Inspiration](#data-pre-processing-steps-and-inspiration)
5. [Choosing the Algorithm](#choosing-the-algorithm)
6. [Motivation for Algorithm Selection](#motivation-for-algorithm-selection)
7. [Assumptions](#assumptions)
8. [Model Evaluation and Techniques](#model-evaluation-and-techniques)
9. [Inferences](#inferences)
10. [Future Possibilities](#future-possibilities)
11. [Conclusion](#conclusion)
12. [References](#references)

---

## Problem Statement
The company is facing financial difficulties, struggling with inventory management, and aligning supply with demand. As a data scientist, the goal is to provide actionable insights and build predictive models to forecast sales over a period of time, aiming to improve operational efficiency.

## Project Objective
The objective is to forecast sales for each Walmart store for the next 12 weeks, providing insights that can help stores optimize their performance.

## Data Description
The dataset contains 6435 rows and 8 columns. Features include:
- **Store**: Store number
- **Date**: Week of sales
- **Weekly_Sales**: Sales for the given store in that week
- **Holiday_Flag**: Indicates if it's a holiday week
- **Temperature**: Temperature on the day of the sale
- **Fuel_Price**: Cost of fuel in the region
- **CPI**: Consumer Price Index
- **Unemployment**: Unemployment rate

## Data Pre-processing Steps and Inspiration
1. Data loading and inspection
2. Conversion of the 'Date' column to datetime format
3. Handling missing data
4. Visualization of sales over time to understand trends

## Choosing the Algorithm
Two algorithms were chosen for this time series forecasting project:
- **ARIMA (Auto-Regressive Integrated Moving Average)**
- **Random Forest**

## Motivation for Algorithm Selection
- **ARIMA**: Ideal for univariate time series data, suitable for capturing temporal structures such as trend and seasonality.
- **Random Forest**: Effective in identifying complex patterns in historical sales data.

## Assumptions
1. The sales data is stationary or has been transformed to become stationary.
2. No external disruptions affect sales beyond the variables considered.

## Model Evaluation and Techniques
The model was evaluated using:
- Data split into training and testing sets.
- Performance metrics: Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

### Key Findings:
- ARIMA captured trend and seasonality better than Random Forest.
- External factors such as holidays and fuel prices significantly impact sales.

## Inferences
The analysis revealed that holidays, fuel prices, and CPI are important variables influencing sales. These insights can be leveraged to optimize inventory and staffing strategies.

## Future Possibilities
Further improvements can be made by incorporating additional external factors such as:
- Promotional campaigns
- Competitor pricing strategies
- Economic trends and market fluctuations

## Conclusion
The project successfully forecasted sales for the next 12 weeks, providing valuable insights for improving store management and overall operational efficiency.

## References
1. "Sales Forecasting using Random Forest Algorithm" by S. Senthilkumar and R. Srinath (2020)
2. "Incorporating External Factors into Sales Forecasting Models: A Systematic Review" by A. Kumar et al. (2022)


