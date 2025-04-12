# 📊 Tesla and GameStop Stock & Revenue Analysis

This project analyzes the historical stock prices and quarterly revenue data of **Tesla (TSLA)** and **GameStop (GME)**. The stock price data is extracted using the `yfinance` Python library, while revenue data is scraped from **Macrotrends** using `BeautifulSoup`.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Data Sources](#data-sources)
- [Project Tasks](#project-tasks)
- [Visualizations](#visualizations)
- [How to Run](#how-to-run)
- [Screenshots](#screenshots)

---

## ✅ Overview

The objective of this project is to:
- Extract stock data for Tesla and GameStop.
- Web scrape quarterly revenue data from reliable financial websites.
- Visualize both stock price trends and revenue growth using side-by-side plots.

---

## 🧰 Technologies Used

- Python 3.x
- [yfinance](https://pypi.org/project/yfinance/)
- [BeautifulSoup4](https://pypi.org/project/beautifulsoup4/)
- [Matplotlib](https://matplotlib.org/)
- [Pandas](https://pandas.pydata.org/)

---

## 📊 Data Sources

- **Stock Price Data**: [Yahoo Finance via yfinance](https://finance.yahoo.com/)
- **Revenue Data**: [Macrotrends](https://www.macrotrends.net/)

---

## 📋 Project Tasks

1. Extract Tesla stock data using `yfinance`.
2. Scrape Tesla quarterly revenue using `BeautifulSoup`.
3. Extract GameStop stock data using `yfinance`.
4. Scrape GameStop quarterly revenue using `BeautifulSoup`.
5. Plot Tesla stock price and revenue side by side.
6. Plot GameStop stock price and revenue side by side.

---

## 📈 Visualizations

Each company’s data is displayed using:
- **Line graph of stock closing price over time**
- **Line graph of quarterly revenue over time**
- **Both graphs shown side-by-side** for comparison

---

## ▶️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/tesla-gme-analysis.git
   cd tesla-gme-analysis
