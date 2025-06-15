# 📊 Stock Correlation Analyzer

A simple Python tool that analyzes the historical correlation between selected stocks using Yahoo Finance data. 

This project was built to practice:

- ✅ API integrations (`yfinance`)
- ✅ Data wrangling (`pandas`)
- ✅ Statistical analysis (`numpy`)
- ✅ Data visualization (`seaborn` & `matplotlib`)
- ✅ Git & GitHub version control
- ✅ Python project structuring

---

## 🚀 Features

- Download historical stock prices using Yahoo Finance
- Calculate daily returns and build correlation matrix
- Generate a heatmap of correlations between stocks
- Export both CSV and image output files

---

## 📂 Project Structure

main.py
requirements.txt
data/
tickers.csv
output/
correlations.csv
heatmap.png

---

## 🧮 Example Tickers (in `data/tickers.csv`)

Ticker
AAPL
MSFT
GOOG
NVDA
META
---

## 💻 Setup Instructions

1️⃣ Install dependencies:

```bash
pip install -r requirements.txt
python main.py
