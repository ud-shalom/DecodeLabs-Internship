# AAPL Stock Analysis Project

This repository documents a comprehensive time-series analysis of Apple Inc. (AAPL) stock, conducted to evaluate market performance, volatility, and historical trends over a five-year period.

## 1. Data Loading
In this initial phase, I utilized the `yfinance` library to download five years of historical trading data for Apple Inc.. This step is foundational as it provides the raw daily data points—including Open, High, Low, Close, and Volume—necessary to build the entire analytical model.

## 2. Data Exploration
I performed an initial exploratory data analysis to inspect the dimensions of the dataset and verify that the data correctly loaded. By checking the shape and information of the DataFrame, I confirmed that I had the complete daily records required for the subsequent analysis.

## 3. Data Cleaning and Preprocessing
To ensure high-quality analysis, I addressed potential data issues by checking for missing values and duplicates. This phase is critical because accurate, clean data is essential for producing reliable insights and trend identifications.

## 4. Data Transformation using Pandas
I flattened the multi-level headers to ensure the data was in a structure that allowed for direct column manipulation. Following this, I extracted the 'Year' from the date index and used `groupby` and `agg` to condense thousands of daily rows into a professional summary table showing yearly volume totals and average closing prices.

## 5. Feature Engineering
I enhanced the dataset by creating new, meaningful metrics. By calculating the 'Daily Price Change' and 'Percentage Change', I was able to quantify the magnitude of market movements. Additionally, I computed a '30-Day Moving Average' to smooth out daily fluctuations and reveal the underlying price trends more clearly.

## 6. Data Visualizations
I developed several visualizations to communicate complex trends effectively. 
* **Stock Price Trend & Moving Averages**: This chart overlays the 30-day moving average against the actual closing price, helping stakeholders distinguish between short-term noise and long-term direction.
* ![Stock Closing Price Trend](PYTHON%202.png)
* **Daily Percentage Change Analysis**: This plot highlights market volatility, showing days of extreme gain or loss.
* ![Daily Returns Analysis](PYTHON%203.png)
* **Volume Distribution**: This visualizes the distribution of trading volume, providing insight into the market activity levels over time.
* ![Distribution of Trading Volume](PYTHON%201.png)

## 7. Key Findings and Conclusions
The analysis demonstrates a clear long-term upward trend in AAPL’s stock value. By calculating the total growth over the five-year period, I confirmed consistent market behavior, providing a solid foundation for further investment analysis.

---

#python #googlecolab #dataanalytics #AAPL #stockanalysis

**Created by: [OKOLI UDOKA SHALOM]**
