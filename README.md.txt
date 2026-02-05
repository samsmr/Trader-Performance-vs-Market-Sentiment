# Trader Performance vs Market Sentiment (Fear vs Greed)

## Objective
Analyze how Bitcoin market sentiment (Fear/Greed) influences trader behavior and performance on the Hyperliquid platform, and derive actionable insights for sentiment-aware trading strategies.

## Data Sources
1. Bitcoin Market Sentiment (Fear/Greed)
2. Hyperliquid Historical Trader Data

(Dataset download links were provided in the assignment email.)

## Methodology
- Cleaned and standardized trade-level data.
- Converted timestamps and aligned both datasets at a daily level.
- Engineered daily trader metrics including PnL, trade frequency, and average trade size.
- Merged trader metrics with daily market sentiment.
- Conducted performance, behavior, and segmentation analysis across Fear and Greed regimes.

## Key Insights
- Trader performance is stronger during Greed periods, while Fear periods exhibit higher downside risk.
- Trade frequency and position sizing increase during Greed and decrease during Fear.
- Frequent and inconsistent traders are more vulnerable during Fear regimes, while consistent traders demonstrate better downside protection.

## Strategy Recommendations
- Adjust trade frequency dynamically based on market sentiment.
- Reduce position sizes during Fear regimes to manage risk.
- Prefer consistent traders during high-uncertainty periods.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/trader_sentiment_analysis.ipynb
