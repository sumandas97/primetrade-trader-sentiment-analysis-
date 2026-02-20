# primetrade-trader-sentiment-analysis-
Data Science intern assignment analyzing Hyperliquid trader performance against Bitcoin Fear/Greed sentiment. Includes data prep, key metrics (PnL, win rate, leverage), segment analysis, insights with charts/tables, and trading strategy recommendations. Jupyter notebook + README for reproducibility.

## 📊 Executive Summary

| Sentiment      | Avg Daily PnL | Win Rate | Trades/Day |
|----------------|---------------|----------|------------|
| **Extreme Greed** | **$5,162**  | **38.6%** | 76       |
| Extreme Fear   | $4,619        | 32.9%    | 134       |
| Fear           | $5,329        | 36.4%    | 98        |
| Greed          | $3,318        | 34.4%    | 78        |
| Neutral        | $3,439        | 35.5%    | 100       |

## 🎯 Key Insights
- **Greed outperforms Fear** by 11% PnL, higher win rates
- **Traders get aggressive** in Greed: larger sizes ($6K+), more trades
- **High-freq traders** gain 8x PnL during Greed vs low-frequency

## 💡 Trading Strategies
1. **Scale up in Greed**: Increase size/frequency during Greed days
2. **Cut exposure in Fear**: Reduce risk for low-frequency traders  
3. **Long bias in Greed**: Favor longs during positive sentiment
