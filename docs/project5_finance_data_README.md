# Finance Data Analysis

## Project 5 — Multi-Domain Data Analysis Portfolio

### Overview
Analysis of 1,500 simulated business-day financial observations from January 1, 2021 to October 1, 2026.

> **Important:** This dataset is simulated for educational and portfolio purposes. Results are not real investment performance or financial advice.

### Analysis Areas
- Price trends
- Daily returns
- Trading volume
- 20-day and 50-day moving averages
- Rolling volatility
- Monthly performance
- Correlation analysis
- Risk indicators
- Data validation

### Key Results
| Metric | Result |
|---|---:|
| Starting Price | 101.04 |
| Ending Price | 686.77 |
| Overall Price Return | 579.68% |
| Average Daily Return | 0.16% |
| Daily Return Volatility | 1.98% |
| Best Daily Return | 7.76% |
| Worst Daily Return | -6.43% |
| Positive Return Days | 53.13% |
| Negative Return Days | 46.80% |
| Bullish MA Days | 61.53% |
| Bearish MA Days | 38.47% |
| Maximum 20-Day Volatility | 3.19% |
| Highest Trading Volume | 999,751 |

### Visualizations
1. `finance_correlation_matrix.png`
2. `finance_price_trend.png`
3. `finance_daily_returns.png`
4. `finance_trading_volume.png`
5. `finance_volatility.png`
6. `finance_monthly_returns.png`
7. `finance_ma_signals.png`

### Insights
- The simulated price increased from 101.04 to 686.77.
- June had the highest calendar-month average daily return at 0.378%.
- January had the lowest at -0.188%.
- Maximum 20-day volatility was 3.19% on June 23, 2025.
- Highest volume was 999,751 on December 18, 2023.
- Bullish moving-average conditions occurred on 61.53% of trading days.
- Volume vs daily return correlation was only 0.045.

### Data Quality
- 1,500 rows × 16 columns
- 0 duplicate rows
- 1,500 unique dates
- 89 expected rolling-window missing values in the original dataset
- Clean analysis dataset: 1,451 rows with 0 missing values
- OHLC consistency checks passed
- All prices and volumes positive

### Tools
Python, Pandas, NumPy, Matplotlib, Jupyter Notebook

### Portfolio Structure
```text
data-analysis-portfolio/
├── data/finance_data.csv
├── notebooks/05_finance_data_analysis.ipynb
├── visualizations/
├── reports/finance_data_analysis_report.pdf
└── docs/project5_finance_data_README.md
```

### Recommendations
1. Monitor price trends using multiple moving averages.
2. Track rolling volatility to identify higher-risk periods.
3. Evaluate both positive and negative return distributions.
4. Investigate unusual trading-volume activity alongside price changes.
5. Combine several indicators rather than relying on one metric.
6. Validate findings against reliable real-world market data before practical use.

### Conclusion
This project demonstrates a complete financial data-analysis workflow from simulation and validation through statistics, trends, volatility, correlations, visualization, and recommendations.
