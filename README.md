# Large-Scale-Data-Management-and-Visualization

## Introduction
This project presents an end-to-end data pipeline that demonstrates how data is collected from a streaming source, processed using AI techniques, and visualized for insights. The core objective is to explore whether the sentiment expressed in financial news articles aligns with market behavior.

Tools & Libraries

1) Python

    Beautiful Soup (URL scraping)

    newspaper3k (Content extraction)

    FinBERT (Sentiment analysis)

    KeyBERT (Keyword extraction)

    BERTopic (Topic modeling)

2) MySQL

3) Power BI
## Workflow

1) Scraping: Articles from Business Insider and OHLCV data via yfinance

2) Processing:

    FinBERT for sentiment

    KeyBERT for keywords

    BERTopic for topic modeling

3) Storage: Data saved in MySQL using SQLAlchemy

4) Visualization: Dashboards in Power BI showing sentiment, topics, and market metrics
