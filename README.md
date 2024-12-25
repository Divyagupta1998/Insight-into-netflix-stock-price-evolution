Project Summary: Financial Forecasting through Predictive Analytics: Insights into Netflix’s Stock Price Evolution

Problem: The goal of this project was to predict the future stock price movements of Netflix, a leading streaming service provider, based on its historical stock data. The challenge was to identify patterns in the stock’s daily performance using various features, including opening price, high, low, closing price, and volume of trades, to forecast future price directions.

Approach: We utilized machine learning models to analyze Netflix’s historical stock data from 2003 to 2024, focusing on predicting the direction of Netflix’s closing stock price. Key attributes such as opening price, high price, low price, and trading volume were examined using:

Linear Regression: To explore the relationship between consecutive day’s closing prices.
Random Forest: To identify the most important factors influencing the closing price.
Data preprocessing included converting dates, handling missing values, and creating a binary target variable to indicate whether the stock’s closing price was higher than the opening price on a given day.

Solution: The Random Forest model revealed that the highest and lowest prices during the day were the most significant predictors of the stock’s closing price, with volume being less influential. The model achieved a root mean squared error (RMSE) of 2.485, indicating that the predictions were typically within $2.85 of the actual closing price.

The study found that despite daily volatility, Netflix's stock showed a strong long-term upward trend, suggesting investor confidence. Our predictive analysis offers valuable insights for financial decision-makers, enhancing their understanding of stock price dynamics and providing a reliable framework for stock forecasting using data-driven models.
