**Project Overview**

This project analyzes the relationship between financial news sentiment and stock price movements for major tech companies (AAPL, MSFT, NVDA, AMZN, GOOG, META). The goal is to combine textual sentiment analysis, quantitative technical indicators, and correlation studies to better understand how news impacts market behavior.

**Key objectives:**

Perform data cleaning and exploratory analysis on news and stock datasets.

Calculate technical indicators using TA-Lib and PyNance to understand stock trends.

Conduct sentiment analysis on news headlines and correlate with daily stock returns.

**Dataset**
1. Financial News Dataset

Columns: headline, url, publisher, date, stock

Over a million rows of financial news articles.

Includes metadata such as publisher and publication time.

2. Stock Price Dataset

Columns: Date, Open, High, Low, Close, Volume

Daily historical prices for AAPL, MSFT, NVDA, AMZN, GOOG, META.

Both datasets were cleaned and normalized, with date columns converted to proper datetime format to align news and stock trading days.

**Tasks Overview**

**Task 1:** Data Cleaning & Exploratory Analysis

Cleaned and prepared news and stock datasets.

Explored headline lengths, publisher activity, and article timing.

Found that most headlines are under 100 characters, with Tuesday–Thursday having the highest news activity.

**Task 2:** Quantitative Analysis Using Technical Indicators

Calculated SMA, EMA, RSI, MACD, Bollinger Bands for all stocks.

Observed similar price movements across companies:

Sharp drop in 2023 followed by gradual recovery in 2024.

META had the most significant drop, Apple had a relatively milder decline.

RSI and MACD analysis revealed frequent momentum cycles, highlighting short-term volatility and regular reversals.

**Task 3:** Sentiment vs Stock Movements
Conducted sentiment analysis using TextBlob and aggregated daily sentiment scores.

Calculated daily returns for all stocks.

Found low but positive correlations between sentiment and returns:

**Dependencies**

Python 3.10+

Pandas

Matplotlib

TA-Lib

TextBlob

PyNance (optional for extended financial metrics)
