# Carbon Market Sentiment Index (CMSI) Project

## Overview
The CMSI Project leverages advanced Natural Language Processing (NLP) techniques and machine learning to analyze sentiments from global news articles related to carbon markets. This data is integrated with carbon pricing information to construct the Carbon Market Sentiment Index (CMSI), providing insights into market trends and helping predict future movements.

## Project Structure
- `/Data`: This directory contains all datasets used in the project, organized by data type and source.
  - `/Carbon Price`: Includes historical carbon pricing data from multiple emissions trading systems (ETS). Data is segmented into original collection files, processed datasets, and final compilation files used for analysis.
  - `/News Articles`: Consists of news articles from 2006 to 2023, extracted through Google News RSS Feeds and processed for sentiment analysis.
  - `/CMSI`: Contains specific datasets used for constructing the Carbon Market Sentiment Index, including normalized indices and statistical summaries.
- `/Code`: Contains Jupyter notebooks and Python scripts used for data collection, preprocessing, sentiment analysis, and CMSI calculation.
- `/IMG`: Additional resources related to the methodology and analytical processes.

## Installation
Install the required dependencies to set up the project:
```bash
pip install -r requirements.txt
```

## Research Method
![CMSI_Research Method](https://github.com/jiatongoo/CMSI_CarbonMarketSentimentIndex/blob/main/IMG/Research%20Method.jpg)
