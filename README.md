# Trader Performance vs Market Sentiment Analysis

## Overview

This project analyzes how market sentiment (Fear vs Greed) affects trader behavior and performance using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index. The objective is to identify patterns in trader profitability, risk, and behavior under different market sentiment regimes and derive actionable trading strategies.

## Objective

The main goals of this project are:

- Analyze trader performance under different market sentiment conditions.
- Study how trader behavior changes during Fear vs Greed markets.
- Identify different trader segments based on behavior and performance.
- Develop data-driven strategy recommendations.
- Build a simple predictive model for next-day profitability.
- Cluster traders into behavioral groups.
- Create a simple dashboard for visualization.

## Dataset

This project uses two datasets:

1. Bitcoin Fear & Greed Index
  - Columns: date, classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)
2. Historical Trader Data (Hyperliquid)
  - Columns include: Account, Execution Price, Size USD, Side, Closed PnL, Fee, Timestamp, Trade ID, etc.

``The datasets were merged on the Date column to analyze trader behavior based on daily market sentiment.``

## How to Run This Project

### 1. Clone the Repository
``
git clone https://github.com/your-username/trader-sentiment-analysis.git
cd trader-sentiment-analysis
``

### 2. Install Requirements
``
pip install -r requirements.txt
``
### 3. Run Jupyter Notebook
``
jupyter notebook
``

Open the notebook and run all cells.

## Project structure
```
├── DATA_SCIENCE_ANALYTICS_TASK.ipynb
├── requirements.txt
├── README.md
├── data/
│   ├── fear_greed_index.csv
│   └── historical_data.csv
└── Output charts-tables/
    ├── pnl_by_sentiment.png
    ├── winrate by sentiment.png
    └── trades by sentiment.png
    └──
    └──
```

### Tools & Libraries Used
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit
