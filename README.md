# News Sentiment Analysis for Financial Forecasting

## Overview

This project focuses on analyzing financial news headlines and historical stock price data to explore the relationship between news sentiment and stock market movements. The analysis was conducted as part of a financial analytics challenge for Nova Financial Solutions.

The main goal of the project is to investigate whether financial news sentiment can provide useful insights for understanding or predicting stock price behavior. The project combines exploratory data analysis (EDA), Natural Language Processing (NLP), technical analysis indicators, and statistical analysis techniques.

---

## Business Objective

Nova Financial Solutions aims to improve predictive analytics capabilities by combining financial news sentiment with historical stock market data.

The project focuses on:

- Understanding patterns in financial news headlines
- Performing sentiment analysis on financial text
- Computing technical indicators from stock price data
- Measuring the relationship between news sentiment and stock market performance
- Generating insights that may support investment decision-making

---

## Project Tasks

### Task 1 — Exploratory Data Analysis (EDA)
- Analyze financial news headlines
- Explore publication trends and publisher activity
- Identify common keywords and financial topics
- Perform time-series analysis of news volume

### Task 2 — Quantitative Stock Analysis
- Load and clean historical stock price data
- Compute technical indicators such as:
  - SMA
  - EMA
  - RSI
  - MACD
- Visualize stock market trends

### Task 3 — Sentiment and Correlation Analysis
- Perform sentiment analysis on headlines
- Calculate stock returns
- Measure correlation between sentiment and stock price movement
- Explore how news sentiment may relate to market behavior

---

## Dataset Description

The project uses two datasets.

### Financial News Dataset
Contains:
- headline
- publisher
- publication date
- stock symbol
- article URL

### Historical Stock Price Dataset
Contains:
- Date
- Open
- High
- Low
- Close
- Adjusted Close
- Volume

---

## Technologies and Libraries Used

### Programming Language
- Python

### Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- nltk
- wordcloud
- ta

### Tools
- Jupyter Notebook
- Git & GitHub
- GitHub Actions
- VS Code

---

## Project Structure

```text
news-sentiment-analysis/
│
├── .github/
│   └── workflows/
│
├── data/
│   └── raw/
│
├── notebooks/
│   ├── financial_news_eda.ipynb
│   └── stock_price_analysis.ipynb
│
├── scripts/
├── src/
├── tests/
│
├── requirements.txt
└── README.md
