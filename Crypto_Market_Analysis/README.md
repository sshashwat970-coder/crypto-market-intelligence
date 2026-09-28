# Crypto Market Intelligence & Price Tracker

A data analytics project that collects cryptocurrency market data using the CoinGecko API, analyzes it using Python and Pandas, and presents the results through an interactive Power BI dashboard.

The project focuses on cryptocurrency market capitalization, trading volume, prices, and price performance across different time periods.

---

## I. Project Overview

Cryptocurrency markets change continuously, making indicators such as price, market capitalization, trading volume, and percentage change useful for understanding market activity.

In this project, cryptocurrency market data was collected using the CoinGecko API and analyzed using Python.

The collected data was cleaned, explored, and visualized using Pandas, Matplotlib, and Seaborn. The processed dataset was then used to create a Power BI dashboard for an interactive view of the market.

The project also contains multiple historical snapshots, allowing cryptocurrency data to be tracked over the collection period.

---

## II. Objectives

The main objectives of this project are:

1. Collect cryptocurrency market data using an API.
2. Clean and organize the collected data using Pandas.
3. Analyze cryptocurrencies based on market capitalization and trading volume.
4. Study cryptocurrency price performance across different time periods.
5. Explore historical cryptocurrency market data.
6. Create visualizations using Matplotlib and Seaborn.
7. Build an interactive Power BI dashboard.
8. Practice an end-to-end data analytics workflow.

---

## III. Tools and Technologies

1. **Python** - Data collection and analysis
2. **Pandas** - Data manipulation and cleaning
3. **Requests** - API requests
4. **CoinGecko API** - Cryptocurrency market data
5. **Matplotlib** - Data visualization
6. **Seaborn** - Statistical visualization
7. **Power BI** - Interactive dashboard
8. **Jupyter Notebook** - Analysis environment
9. **Git and GitHub** - Version control and project management

---

## IV. Project Workflow

1. Data collection using the CoinGecko API
2. Data preparation using Python and Pandas
3. Data cleaning and validation
4. Historical data collection
5. Exploratory data analysis
6. Data visualization using Python
7. Dataset preparation for Power BI
8. Interactive dashboard development
9. Analysis of market indicators

---

## V. Dataset

The project uses cryptocurrency market data collected from the CoinGecko API.

The dataset contains information such as:

- Cryptocurrency ID
- Symbol
- Name
- Current Price
- Market Capitalization
- Market Capitalization Rank
- Trading Volume
- 1H Price Change
- 24H Price Change
- 7D Price Change
- 14D Price Change
- 30D Price Change
- 200D Price Change
- 1Y Price Change
- Timestamp

The final historical dataset contains 225 records covering 25 cryptocurrencies across 9 snapshots.

---

## VI. Exploratory Data Analysis

The Python analysis was used to explore different aspects of the cryptocurrency market.

### Analysis Performed

1. Top cryptocurrencies by market capitalization
2. Top cryptocurrencies by trading volume
3. 24-hour cryptocurrency performance
4. Top 10 cryptocurrencies by 24-hour performance
5. Top cryptocurrencies by price
6. Historical price movement of the highest-ranked cryptocurrency

These analyses were used to understand differences in market size, trading activity, and recent price performance.

---

## VII. Power BI Dashboard

The final Power BI dashboard provides a high-level overview of the cryptocurrency market.

### KPI Cards

1. Latest Market Cap
2. Latest Trading Volume
3. Latest Coin Count
4. Last Updated Timestamp

### Visualizations

1. Top 10 Cryptocurrencies by Market Capitalization
2. Top 10 Cryptocurrencies by Trading Volume
3. Top 10 24H Cryptocurrency Performance

### Market Table

The dashboard table contains:

1. Cryptocurrency
2. Price
3. Market Capitalization
4. Trading Volume
5. 24H Change
6. 7D Change
7. 30D Change

### Filters

1. Cryptocurrency
2. Market Cap Rank

---

## VIII. Dashboard Preview

![Crypto Market Intelligence Dashboard](screenshots/crypto-dashboard.png)

---

## IX. Key Insights

The analysis provides a view of how cryptocurrencies differ in terms of market size, trading activity, and recent price performance.

The project examines:

1. Cryptocurrencies with the highest market capitalization
2. Cryptocurrencies with the highest trading volume
3. Cryptocurrencies with the largest 24-hour price changes
4. Differences in performance across multiple time periods
5. Historical price movement across the collected snapshots

The values shown in the dashboard represent the data available during the collection period and may change as market conditions change.

---

## X. Project Structure

```text
crypto-market-intelligence/
│
├── Crypto Market Intelligence & Price Tracker.ipynb
├── crypto_historical_data.csv
├── README.md
├── .gitignore
│
└── screenshots/
    └── crypto-dashboard.png