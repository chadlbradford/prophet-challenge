
# README: Google Search Trends and Stock Analysis Project

## Overview
This project explores the relationship between Google search trends and MercadoLibre's stock data. Using tools like Pandas, Prophet, and Matplotlib, the notebook performs data analysis to uncover patterns in search behavior, identify seasonality, and correlate these trends with stock price movements. A time series forecasting model is also built using Prophet to predict future search traffic.

## Grading Criteria
The notebook is graded using the following criteria:

### **Find Unusual Patterns in Hourly Google Search Traffic (25 points)**
1. **Read the search data into a DataFrame** (5 points): Successfully loading the dataset with appropriate datetime parsing and initial cleaning.
2. **Slice the data to just the month of May 2020** (5 points): Isolating the desired month for detailed analysis.
3. **Calculate the total search traffic for the month** (5 points): Summing the traffic values for May 2020.
4. **Compare the value to the monthly median across all months** (5 points): Using resampling to calculate the monthly median and comparing it to May 2020.
5. **Did the search traffic increase during the month MercadoLibre released financial results?** (5 points): Analyzing trends during key financial reporting periods.

### **Mine the Search Traffic Data for Seasonality (20 points)**
1. **Group the hourly search data to plot the average traffic by the hour of day** (5 points): Aggregating and visualizing search traffic by hour.
2. **Group the hourly search data to plot the average traffic by the day of the week** (5 points): Identifying daily patterns.
3. **Group the hourly search data to plot the average traffic by the week of the year** (5 points): Uncovering weekly trends.
4. **Are there time-based trends in the data?** (5 points): Written observations based on visualizations.

### **Relate the Search Traffic to Stock Price Patterns (35 points)**
1. **Read in and plot the stock price data** (5 points): Loading and visualizing stock prices.
2. **Concatenate the stock price data with the search data** (5 points): Merging the datasets.
3. **Slice data for the first half of 2020 and plot it** (5 points): Focused analysis on January to June 2020.
4. **Create a "Lagged Search Trends" column** (5 points): Shifting search trends data by one hour.
5. **Create "Stock Volatility" and "Hourly Stock Return" columns (10 points): Calculating new metrics based on stock data.
6. **Does a predictable relationship exist between lagged search traffic and stock price metrics?** (5 points): Written analysis.

### **Create a Time Series Model with Prophet (20 points)**
1. **Set up the search data for a Prophet model** (5 points): Preparing and cleaning data for forecasting.
2. **Plot the forecast** (5 points): Visualizing the Prophet model’s predictions.
3. **Plot individual time series components** (5 points): Decomposing the time series into trend, seasonality, and residuals.
4. **Answer specific questions about search trends** (5 points): Written responses to questions on traffic patterns.

## Features
- **Data Preparation**: Cleans and processes Google search and stock data.
- **Seasonality Analysis**: Visualizes hourly, daily, and weekly patterns.
- **Stock Data Analysis**: Examines relationships between search traffic and stock price movements.
- **Forecasting**: Uses Prophet to predict future search trends.

## Requirements
To run the notebook, you need the following dependencies:
- Python 3.7+
- Pandas
- Matplotlib
- Prophet

Install them using:
```bash
pip install pandas matplotlib prophet
```

## Instructions
1. Clone the repository or download the notebook.
2. Open the notebook in Jupyter Notebook or any compatible environment.
3. Run the cells sequentially.
4. Review visualizations and written insights for analysis.

## Outputs
The notebook generates:
1. Visualizations of search traffic trends.
2. Correlations between search traffic and stock price metrics.
3. Prophet forecasts and time series component analysis.

## References
- Self-sourced code was vetted and debugged using ChatGPT.
- Stock and search trend data sourced from publicly available datasets.
- Python library documentation for Pandas, Matplotlib, and Prophet.
