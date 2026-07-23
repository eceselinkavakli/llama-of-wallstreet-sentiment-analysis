# 🦙 The LLAMA of Wall Street: Reddit Stock Sentiment Analysis

> **Bologna Business School - Big Data Laboratory Team Project (2026)**
> *Scalable Financial Sentiment Extraction utilizing Open-Source LLMs and High-Performance Computing.*

---

## 📖 Executive Summary
The **LLAMA of Wall Street** is an end-to-end Natural Language Processing (NLP) pipeline designed to extract structured, daily stock-sentiment signals from unstructured social media data. Processing approximately **100,000 raw Reddit comments**, this project moves beyond traditional keyword-based sentiment by leveraging advanced Large Language Models (LLMs) to capture the nuanced financial context of retail investors.

## 🏗️ Technical Architecture & Methodology
Engineered for high-throughput data processing and scalable execution, the pipeline features:
* **Asynchronous NLP Pipeline:** Implemented an asynchronous **RoBERTa-based sentiment analysis** workflow to ensure rapid and accurate baseline emotion classification.
* **Advanced Information Extraction:** Deployed locally-hosted, open-source LLMs to perform complex entity recognition and structured sentiment scoring.
* **High-Performance Computing (HPC):** Initial prototyping and integrations were developed via Google Colab, while final distributed processing was executed at scale on the **Leonardo supercomputer (CINECA)** cluster.
* **Data Engineering:** Robust Python pipelines designed to handle noisy web data, address missing values, and aggregate time-series sentiment logic.

## 📂 Repository Contents

| File | Description |
| :--- | :--- |
| `notebook.ipynb` | Core Jupyter Notebook detailing data ingestion, NLP preprocessing, LLM integration, and asynchronous inference. |
| `presentation.html` | Comprehensive slide deck outlining the business problem, methodology, and analytical insights. |
| `results_raw.csv` | Initial unfiltered dataset containing raw Reddit comments and metadata. |
| `reddit_comments_tail.csv` | A semi-processed subset utilized for model validation and testing. |
| `results_daily_sentiment.csv` | Final output dataset featuring aggregated daily sentiment scores grouped by stock ticker. |



## 📊 Overall Sentiment by Ticker
![Summary sentiment bar chart](summary_sentiment_bar.png)

## 📈 Tesla (TSLA) Sentiment Trend
![TSLA sentiment trend](TSLA_sentiment.png)

## 📈 Boeing (BA) Sentiment Trend
![BA sentiment trend](BA_sentiment.png)

## 👥 Contributors
* **Ece Selin Kavakli**
* **Tin Asavasapphavat**
* **Ahmed Mahmoud**
* **Vinicio Zanon Santon**

