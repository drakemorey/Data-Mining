# Data Mining: A Stock Strength Indicator With Predictive Power
Final project for Applied Data Mining:

This project is an attempt to utilize an individual stock (like AMZN or TSLA) along with various broad based / sector ETF's (like SPY or QQQ) that contain said individual stock to produce a new inisght (a stock strength indicator) and make daily up / down return preidcitons. Multiple features are engineered to remove stock data seasonality (engineered features are various technical indicators such as MACD), data is split train/test (80/20), and a binary logistic regression with stepwise variable slection is performed. The fitted values are used to create the stock strength indicator, and model evaluation methods are used to test the model's predictions. 


There are two origins for the data used in the analysis. Firstly, historical data is pulled from Yahoo Finance via the quantmod package in R, and the SPX put/call dataset can be obtained from CBOE: https://www.cboe.com/us/options/market_statistics/historical_data/.

Link to project report:
