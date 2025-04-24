# Stock-Performance-Insight-Engine-A-Visual-Decision-Support-Tool-for-Retail-Investors


This project explores how major tech stocks perform from a retail investor’s perspective using core data analysis tools — NumPy, Pandas, and Matplotlib. The focus is on generating practical investment insights through visual storytelling, clean analysis, and simple simulations, without relying on machine learning or complex forecasting.

## Objective

To build a data-driven, visually rich decision support tool that helps answer key investment questions like:

- Which stock delivered the highest return?
- How consistent and risky were those returns?
- Are there seasonal patterns in performance or volume?
- Can we detect abnormal investor behavior using volume spikes?
- What would a passive $1000 investment have returned?

## Dataset

The dataset contains daily stock price and volume data for four companies: AAPL, MSFT, GOOG, and NFLX. Columns include:

- Date, Ticker
- Open, High, Low, Close
- Adjusted Close
- Trading Volume

## Tools Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Key Features

- Cleaned and transformed time-series data with rolling metrics and cumulative returns
- Visual comparison of stock performance, volatility, and drawdowns
- Z-score based anomaly detection for volume and price movements
- Seasonal trend analysis for both returns and investor activity
- Passive investment simulation showing how a $1000 investment grows over time

## Project Structure

- `notebook.ipynb`: Full analysis and visualizations in Google Colab-compatible format
- `stocks.csv`: Raw dataset used
- `README.md`: Overview and guidance

## Takeaways

- Microsoft and Apple provided the strongest return-risk profiles
- March showed consistent gains across all stocks, while February underperformed
- Anomaly detection can highlight sentiment shifts and event-driven activity
- A simple buy-and-hold strategy favored MSFT and AAPL in this timeframe

