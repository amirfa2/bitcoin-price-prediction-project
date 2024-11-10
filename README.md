# bitcoin-price-prediction-project

This project contains a comprehensive analysis of Bitcoin price prediction using machine learning models and a comparative study between Bitcoin and Apple Inc. stock (AAPL) to understand the distinct characteristics of cryptocurrency and traditional stock markets. 

This project aims to:

1-Predict Bitcoin prices using three machine learning models:
.Linear Regression: Provides a baseline prediction but lacks flexibility in capturing Bitcoin's volatility.
.Random Forest Regressor: Captures non-linear patterns with improved accuracy.
.LSTM (Long Short-Term Memory) Neural Network: Models sequential dependencies in time-series data for higher predictive accuracy.
2-Compare Bitcoin and Apple (AAPL) markets to illustrate their unique characteristics in terms of volatility, trading volume, and investor behavior in Tableau(over the last decade).

Data Sources
Bitcoin Data:
.Historical Data (2014-2022): Collected from Kaggle’s Bitcoin historical data.
.Recent Data (2022-present): Sourced from the CryptoCompare API.
Apple Stock Data:
.Collected from Investing.com, covering the same time range as the Bitcoin dataset to enable a direct comparison.(https://www.investing.com/equities/apple-computer-inc-historical-data)

Model Selection and Insights:
.Linear Regression serves as a simple baseline model, but it struggles to capture Bitcoin’s non-linear and volatile price movements.
.Random Forest Regressor improves accuracy by capturing complex patterns.
.LSTM Model achieves the lowest RMSE, effectively modeling Bitcoin’s time-dependent trends, making it the preferred choice for price prediction.

Tableau Dashboard Overview:
1-Average Price: Bitcoin started with an average price of $344 in 2014, compared to Apple’s $28, with Bitcoin showing significantly more price volatility over time.
2-Standard Deviation: Bitcoin’s high standard deviation range (24 to 10,200) highlights its volatility, while Apple’s narrower range (0.6 to 21) illustrates a more stable growth pattern.
3-Correlation Between Price and Volume: Positive correlation in Bitcoin’s data suggests increased market interest with price rises, whereas Apple’s negative correlation reflects a stable, long-term investment appeal.
4-Total Volume Traded: Apple’s total traded volume, reaching 3.6 trillion dollars, showcases a deeper, more liquid market compared to Bitcoin’s volume of under 0.5 trillion dollars.

Conclusion:
The comparative analysis and prediction models reveal the stark contrasts between Bitcoin and Apple’s market behaviors. Apple’s stable growth and deep market make it attractive to traditional, risk-averse investors, while Bitcoin’s high volatility and rapid growth appeal to those willing to engage in a high-risk, high-reward environment. This repository underscores the need for advanced modeling techniques, like LSTMs, to predict prices in volatile markets effectively.

View the presentation here: https://docs.google.com/presentation/d/1c4GekwMa60iV31noQYOEVTvo2hz9lBrOiflla8sDcfU/edit#slide=id.p