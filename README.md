# AI-Powered Stock News Sentiment & Summarization System

## Overview
Stock prices are strongly influenced by company-related news, public perception, and overall market sentiment. With a large volume of financial news published daily, manual analysis becomes inefficient and error-prone.

This project presents an AI-powered system that analyzes financial news related to a NASDAQ-listed company, determines sentiment polarity, generates weekly sentiment summaries, and correlates sentiment trends with stock price movements (OHLCV). The goal is to provide actionable insights to support informed trading and investment decisions.

## Objectives
- Analyze historical financial news to determine market sentiment
- Classify news sentiment into Positive, Neutral, and Negative categories
- Generate weekly sentiment summaries using NLP techniques
- Correlate sentiment trends with stock price movements
- Assist analysts in data-driven trading and investment strategies

## Dataset Description

### Data Dictionary
- Date: Date when the news article was released
- News: Text content of the financial news article
- Open: Stock price at market opening 
- High: Highest stock price of the day 
- Low: Lowest stock price of the day 
- Close: Adjusted closing stock price 
- Volume: Number of shares traded during the day
- Label: Sentiment polarity of the news article

### Sentiment Labels
- 1  : Positive
- 0  : Neutral
- -1 : Negative

## Technology Stack
- Programming Language: Python
- Libraries and Tools:
  - Pandas, NumPy
  - NLTK / SpaCy / TextBlob / VADER
  - Scikit-learn
  - Matplotlib, Seaborn
  - Transformers (optional for summarization)
- Version Control: Git and GitHub

## Methodology
1. Data Preprocessing
   - Text cleaning and normalization
   - Stopword removal
   - Tokenization and lemmatization

2. Sentiment Analysis
   - Rule-based or machine learning-based sentiment classification
   - Assignment of sentiment polarity to news articles

3. Weekly Sentiment Aggregation
   - Grouping news articles by week
   - Calculation of average sentiment scores
   - Generation of weekly summaries

4. Stock Price Correlation
   - Comparison of sentiment trends with OHLCV stock data
   - Identification of sentiment-driven price movements

5. Visualization and Insights
   - Sentiment versus price trend analysis
   - Volume and volatility analysis

## Key Features
- Automated sentiment analysis of financial news
- Weekly sentiment trend generation
- Correlation analysis between sentiment and stock price movements
- Clear and interpretable data visualizations
- Scalable design for multiple companies

## Future Enhancements
- Real-time financial news scraping
- Advanced deep learning models such as BERT or FinBERT
- Interactive dashboard using Streamlit or Power BI
- Multi-company and sector-wise analysis

## Acknowledgements
- NASDAQ historical stock price data
- Open-source NLP libraries and tools
- Publicly available financial news sources
