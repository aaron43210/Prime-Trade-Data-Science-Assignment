# Prime Trade Data Science Assignment: Market Sentiment vs. Trader Performance

This repository contains my submission for the Prime Trade Data Science Internship assignment. The goal of this analysis is to explore the relationship between trader performance on Hyperliquid and the Bitcoin Fear & Greed Index.

## Files Included
* `analysis.ipynb`: A Jupyter Notebook containing the data cleaning, merging, and full analysis.
* `sentiment_analysis.png`: A 4-panel visualization summarizing the findings.

## Key Insights
1. **Best Market Conditions**: Traders saw the highest win rate (46.5%) and best average PnL ($67.89) during "Extreme Greed" market phases.
2. **Buy vs. Sell**: Sellers significantly outperformed buyers during both "Greed" and "Extreme Greed" phases.
3. **Correlation**: The overall correlation between the daily Fear & Greed index value and daily PnL was very weak (-0.083), indicating that sentiment alone is not a strong linear predictor of overall returns on a daily basis.

## Tech Stack
* Python (pandas, numpy)
* Matplotlib (for visualizations)
* Jupyter Notebook
