# Large-Scale-Data-Management-and-Visualization

## Introduction
This project presents an end-to-end data pipeline that demonstrates how data is collected from a streaming source, processed using AI techniques, and visualized for insights. The core objective is to explore whether the sentiment expressed in financial news articles aligns with market behavior.

Tools & Libraries

    Python

    Beautiful Soup (URL scraping)

    newspaper3k (Content extraction)

    FinBERT (Sentiment analysis)

    KeyBERT (Keyword extraction)

    BERTopic (Topic modeling)

    MySQL

    Power BI
## Workflow

    Scraping: Articles from Business Insider and OHLCV data via yfinance

    Processing:

        FinBERT for sentiment

        KeyBERT for keywords

        BERTopic for topic modeling

    Storage: Data saved in MySQL using SQLAlchemy

    Visualization: Dashboards in Power BI showing sentiment, topics, and market metrics
