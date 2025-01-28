# Sentimental Analysis of Federal Reserve FOMC Meeting Minutes using FinBert

This project aims to analyze the sentiment of Federal Reserve FOMC meeting minutes using FinBert, a pre-trained language model for financial text. The goal is to explore the correlation between the sentiment of meeting minutes and the performance of the S&P 500 index.

## Project Overview

The project involves the following steps:

1. **Web Scraping:** Federal Reserve Open Market Committee meeting minutes are web scraped using the `FedTools` package.
2. **Sentiment Analysis:** FinBert is used to analyze the sentiment of each sentence in the meeting minutes. The positiveness score is calculated as "(no. of positive sentences - no. of negative sentences)/total number of sentences in a minute".
3. **Data Processing:** The positiveness scores are stored in a pandas DataFrame. Historical S&P 500 data is retrieved using `yfinance`.
4. **Visualization:** The sentiment of FOMC meeting minutes is visualized over time. The correlation between sentiment and S&P 500 performance is explored using scatter plots.
5. **Conclusion:** Based on the analysis, conclusions are drawn about the relationship between FOMC meeting sentiment and market performance.

## Findings

Preliminary findings suggest that there may be a negative correlation between the sentiment of FOMC meeting minutes and the performance of the S&P 500 index. However, further analysis is needed to confirm this relationship and to explore potential investment strategies based on these findings.

## Getting Started

To run this project, you will need to:

1. Install the required packages:
