# Trader Performance vs Market Sentiment
### Primetrade.ai — Data Science Intern Assignment

## Objective
Analyze how Bitcoin market sentiment (Fear/Greed) relates to trader behavior and performance on Hyperliquid.

## Datasets
| Dataset | Rows | Columns |
|---------|------|---------|
| Fear/Greed Index | 2,644 | 4 |
| Hyperliquid Trader Data | 2,11,224 | 16 |

## Setup & How to Run
1. Clone this repository
2. Install libraries:
pip install pandas numpy matplotlib seaborn
3. Open notebook.ipynb in Jupyter
4. Run all cells in order

## Methodology
- Loaded and cleaned both datasets
- Aligned by date and merged on common dates
- Created metrics: PnL, Win Rate, Long/Short Ratio, Trade Segments
- Analyzed behavior across 5 sentiment categories

## Key Insights
1. Extreme Greed = Best Performance — Highest Avg PnL $67.9 and Win Rate 46.5%
2. Fear days = Most Active — 61,837 trades during Fear
3. Infrequent traders outperform — Avg PnL $173 vs Frequent $38
4. Fear = Long Bias — 65.7% long positions during Fear days
5. High size traders dominate — $242 avg PnL during Extreme Greed

## Strategy Recommendations
1. Increase position size during Extreme Greed (index 75+)
2. Trade selectively — fewer high-confidence trades = better returns

## Author
Aisha Sayyad | Data Analyst
GitHub: github.com/aishasayyad9797-maker
