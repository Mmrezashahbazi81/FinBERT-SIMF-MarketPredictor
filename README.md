# 📈 FinBERT-SIMF-MarketPredictor

An open-source Python framework for financial market price prediction using informative technical indicators and news sentiment.

This project is based on the article:  
**“Investigating the Informativeness of Technical Indicators and News Sentiment in Financial Market Price Prediction”**  
It implements the core methodology proposed in the study, combining FinBERT-based sentiment analysis with RNN-based regression on Forex and Crypto markets.

---

## 🔍 Overview

This framework integrates:
- Web scraping of financial news and market data
- Sentiment scoring using FinBERT (fine-tuned for financial text)
- Technical indicator extraction (e.g., RSI, MACD, Bollinger Bands)
- Information Gain (IG) for feature selection
- Time-aligned sentiment and market data fusion
- RNN-based regression model for price prediction
- Evaluation using z-score normalization and MAPE

---

## 🧰 Features

- ✅ Scrapes real-time news headlines and OHLCV market data
- ✅ Computes FinBERT-based sentiment scores
- ✅ Extracts and selects technical indicators using IG
- ✅ Aligns sentiment and market data by timestamp
- ✅ Trains RNN to jointly learn from sentiment and technical signals
- ✅ Evaluates model robustness using z-score and error metrics

---


