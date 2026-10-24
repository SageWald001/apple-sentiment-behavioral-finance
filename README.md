# apple-sentiment-behavioral-finance
Analyzing the relationship between Apple news sentiment and stock price movements using Python and VADER NLP.

Project Overview:
Inspired by Professor Robert Shiller’s coursework on Financial Markets and my interest in behavioral economics, this project explores whether the emotional tone of financial news headlines is related to short-term stock price movements for Apple Inc. (AAPL).

The goal is to investigate how news sentiment and human psychology might influence market behavior by comparing sentiment scores from historical news headlines with actual daily stock market data.

Tech Stack & Libraries:

Language: Python

Data Manipulation & Cleaning: Pandas, NumPy

Market Data: yfinance

Sentiment Analysis: vaderSentiment (VADER)

Data Visualization: Matplotlib

Methodology

Data Collection: Retrieved historical daily stock prices and trading volume for Apple (AAPL) using yfinance and calculated daily percentage returns. I also used a multi-year dataset of Apple news headlines from Kaggle.

Sentiment Analysis: Used VADER to assign each headline a compound sentiment score ranging from -1 (most negative) to +1 (most positive).

Data Cleaning & Integration: Standardized dates, cleaned financial data column indexes, and merged the stock market data with daily average news sentiment scores using Pandas.

Visualization: Created a time-series chart with two y-axes to compare changes in stock prices with fluctuations in daily news sentiment.

Key Findings & Takeaways

Sentiment vs. Stock Performance: The visualization did not reveal a clear, consistent relationship between daily news sentiment and short-term stock price movements.

The Complexity of Market Behavior: This project highlighted that financial markets are influenced by more than just whether news is positive or negative. Although sentiment may be one factor in market behavior, stock prices can also reflect broader economic conditions, investor expectations, and other influences.

Limitations & Next Steps: This initial analysis focuses on visual comparisons and does not establish a causal relationship between news sentiment and stock performance. Further analysis could explore statistical correlations, time lags between news and price movements, and whether sentiment has different effects under different market conditions.
