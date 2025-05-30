# 🧠 Financial News Sentiment & Stock Correlation Analysis

This project focuses on analyzing financial news headlines to extract sentiment signals and explore their correlation with stock market movements. Designed as a multi-disciplinary challenge, it emphasizes **Data Engineering (DE)**, **Financial Analytics (FA)**, and **Machine Learning Engineering (MLE)** within a high-pressure, real-world financial context.

---

## 📌 Business Objective

**Nova Financial Solutions** aims to enhance its predictive analytics capabilities to improve forecasting accuracy and operational efficiency. The goals of this project are:

- 📊 Quantify sentiment from financial news headlines.
- 📈 Correlate sentiment trends with stock price movements.
- 💡 Derive actionable investment strategies based on insights.

---

## 🚀 Tasks Overview

### ✅ Task 1: Setup & Git

- Set up a reproducible Python environment.
- Create and switch to a branch named `task-1`.
- Push code to GitHub regularly (min. 3 commits/day).
- Use GitHub Actions for CI/CD with `unittests.yml`.

---

## 📊 Exploratory Data Analysis (EDA)

- **Descriptive Statistics**: Headline lengths, article frequency by publisher, time trends.
- **Text Analysis**: Keyword extraction and topic modeling using NLP.
- **Time Series Analysis**: News volume over time, spike detection, and publishing patterns.
- **Publisher Analysis**: Top publishers, domain extraction from emails, and topic distribution.

---

## 🛠️ Tools & Libraries

- `pandas`, `numpy`, `matplotlib`, `seaborn` – Data handling and visualization
- `nltk`, `scikit-learn`, `spaCy` – Natural Language Processing
- `TA-Lib`, `PyNance` – Technical indicators
- `pytest` – Testing
- `GitHub Actions` – CI/CD

---

## 📁 Data

**FNSPID** – Financial News and Stock Price Integration Dataset  
Includes:
- `headline`: News title
- `publisher`: Author/creator of the article
- `date`: Publication timestamp (UTC-4)
- `stock`: Stock ticker
- `url`: Link to the full article

Place raw CSVs in `data/raw/`.

---# financial-news-sentiment-stock-correlation
