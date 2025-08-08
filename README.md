
# 📊 Trader Behavior vs Bitcoin Market Sentiment

This project analyzes how market sentiment — derived from the Bitcoin Fear & Greed Index — impacts trader behavior on the Hyperliquid platform.

## 📁 Dataset Overview

1. **Historical Trader Data (Hyperliquid)**  
   - Columns: `Account`, `Side`, `Execution Price`, `Closed PnL`, `Size USD`, `Timestamp`, etc.

2. **Fear & Greed Index**  
   - Columns: `date`, `classification` (`Fear`, `Greed`, `Extreme Fear`, etc.)

## 🔍 Objective

- Merge sentiment data with trader execution logs.
- Identify patterns in profitability across sentiment phases.
- Visualize and interpret trader behavior under bullish/bearish conditions.
- Highlight top traders and their sentiment-aware strategies.

## 📈 Key Insights

- **Extreme Greed days yield the highest average PnL**.
- Most trades across all sentiments have a median PnL of ~$0 (scalping/breakeven behavior).
- Top traders adapt differently: some thrive in bearish conditions too.

## 📂 Files

- `Trader_Sentiment_Insights.ipynb`: Main analysis notebook with code, plots, and insights.
- `historical_data.csv`: Raw trader logs.
- `fear_greed_index.csv`: Daily sentiment classifications.

## ▶️ How to Run

1. Clone the repo or download this folder.
2. Open `Trader_Sentiment_Insights.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells to reproduce the analysis.



