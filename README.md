## Trader Performance vs Market Sentiment

This project explores the relationship between **trader performance** and **market sentiment** (using the Fear & Greed Index).
It uses Python to uncover hidden patterns and generate insights that can help drive smarter trading strategies.

## Features

- Cleans and processes raw trade history + sentiment index data.

- Computes **per-trader performance metrics** (win rate, Sharpe-like ratio, etc.).

- Aggregates **daily returns** and links them with sentiment data.

- Measures **lagged correlations** between sentiment and returns.

- Runs **per-trader regressions:** Do certain traders follow sentiment better?

- Performs **event studies** around extreme sentiment days (Fear/Greed extremes).

- Clusters traders into groups using **K-Means**.

- Builds a simple **predictive model** (Logistic Regression) to classify trade outcomes.

- Outputs **CSV files + plots** for analysis.




## Key Outputs

- **Per-Trader Summary** (per_trader_summary.csv)

      Trades, win rate, average return, Sharpe-like ratio.

- **Merged Daily Sentiment & Returns** (merged_daily_sentiment_returns.csv)

      Links daily mean returns with sentiment index.

- **Lagged Correlations** (lagged_correlations.csv)

      - Shows how sentiment leads/lags daily performance.

- **Rolling Correlation Plot** (rolling_corr.png)

      - Time-varying relationship between sentiment and trader returns.

- **Scatter Plot** (sent_vs_ret_scatter.png)

      - Visual link between sentiment and daily returns.

- **Event Study** (event_study_extreme_sentiment.csv, plots)

      - Market performance around extreme fear/greed days.

- **Trader Clusters** (per_trader_clusters.csv)

      - Groups of traders based on behavior and performance.

- **Predictive Model Outputs** (predictive_model_metrics.csv, predictive_model_coefs.csv)

      - Classification model predicting win/loss outcomes.





  
