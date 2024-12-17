# W1 Financial Analysis Project

# Project Title: Comprehensive Financial Analysis and Stock Price Sentiment Correlation

## Overview
This project analyzes historical stock data for prominent tech companies (AAPL, AMZN, GOOG, META, MSFT, NVDA, TSLA) and explores the correlation between stock price movements and sentiment derived from financial news headlines. The goal is to uncover insights into the relationship between stock performance and public sentiment.

## Summary Report

### Objective
The primary objective of this project is to evaluate the historical performance of tech stocks by analyzing stock price data and sentiment from financial news. This analysis aims to provide actionable investment insights and refine data analysis methodologies.

### Methods
- **Data Collection**: Stock data for seven tech companies and financial news headlines for Apple Inc. were collected.
- **Sentiment Analysis**: News headlines were analyzed using TextBlob to assign sentiment scores.
- **Stock Price Movement Analysis**: Daily stock returns were calculated, and Pearson correlation coefficients were used to measure the relationship between sentiment and stock prices.
- **Exploratory Data Analysis (EDA)**: Correlation matrices, heatmaps, and time-series decomposition were used to analyze stock data trends.
- **Outlier Detection & Error Handling**: Statistical methods were applied to detect extreme values and handle missing or corrupted data.

### Key Findings
- **Sentiment Analysis**: Apple news headlines had an average sentiment score of 0.05, indicating a neutral sentiment overall. Stock price movements were highly volatile, influenced by earnings reports and market conditions.
- **Correlation Analysis**: A weak positive correlation (0.12) was found between sentiment scores and stock returns, suggesting that sentiment has limited predictive power on stock price movements.
- **Visualization Insights**: Scatter plots and heatmaps illustrated weak correlations. Seasonal analysis of stock data showed significant price movements for companies like NVDA and TSLA during Q4.

### Challenges and Gaps
- **Data Quality Issues**: Missing and inconsistent data affected both stock and sentiment datasets.
- **Visualization Clarity**: Some charts lacked clear labeling and legends.
- **Error Handling**: Incomplete data handling could lead to runtime issues.

### Recommendations
- **Enhance Visualizations**: Introduce candlestick charts and better visual annotations.
- **Improve Sentiment Analysis**: Explore advanced tools like VADER or BERT for more accurate sentiment analysis.
- **Advanced Techniques**: Implement machine learning models for predicting stock prices and use ARIMA models for time-series forecasting.

## Technologies Used
- Python
- Pandas
- Matplotlib
- TextBlob (for sentiment analysis)
- Jupyter Notebook

## Installation Instructions
1. Clone the repository: `git clone https://github.com/Kassa-Mamo/W1FinancialAnalysis.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the project: `python analysis.py`

## Usage
- To analyze stock data and sentiment, run the following command: `python analysis.py`

## Contributing
Feel free to submit pull requests, file issues, or suggest improvements!

## License
MIT License

