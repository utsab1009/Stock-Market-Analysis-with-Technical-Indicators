# Stock-Market-Analysis-with-Technical-Indicators
This project analyzes historical stock market data to generate buy/sell signals using popular technical indicators like RSI, MACD, and Moving Averages. It fetches real-time financial data using Yahoo Finance API and visualizes market trends with candlestick charts.
## 💡 Key Features
- Real-time stock data fetching using `yfinance`
- Calculation of RSI (Relative Strength Index)
- MACD (Moving Average Convergence Divergence) strategy
- EMA (Exponential Moving Average) and SMA (Simple Moving Average)
- Signal generation logic for Buy/Sell decisions
- Candlestick chart visualization with Plotly

## 📊 Output
- Daily stock trend analysis
- Plotted MACD/RSI curves
- Candlestick chart with moving average overlays
- Buy/Sell signal annotations

## 🧠 Tech Stack
`Python`, `yfinance`, `Pandas`, `Numpy`, `Matplotlib`, `Plotly`, `TA-Lib` (optional)

## 🚀 Sample Use Case
```python
# Run this to analyze TATASTEEL:
python stock_analysis_dp.py
📂 Project Structure
Copy
Edit
📦 stock-market-analysis
 ┣ 📜 stock_analysis_dp.py
 ┣ 📄 README.md
 ┗ 📊 outputs/
