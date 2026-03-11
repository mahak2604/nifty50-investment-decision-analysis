# Investment Decision Analysis using Statistical Models

This project analyzes historical NIFTY 50 market data to understand how investors can make rational decisions under uncertainty using statistical modelling and decision theory.

## Objective
To identify the most effective investment strategy by analyzing market states and applying statistical decision-making models.

## Dataset
- Source: NIFTY 50 Historical Data
- Period: 2000–2025
- Observations: ~6000 daily records
- Variables: Date, Open, High, Low, Close, Volume

## Methodology

1. Data preprocessing and calculation of monthly returns
2. Market state classification:
   - Bull Market (> +1%)
   - Bear Market (< -1%)
   - Neutral Market (-1% to +1%)

3. Strategy evaluation using decision models:
   - Maximin
   - Maximax
   - Minimax Regret
   - Expected Monetary Value (EMV)
   - Bayesian Updating

## Key Findings

- Momentum strategy showed the best expected performance.
- It produced the highest Expected Monetary Value (EMV).
- Bayesian updating further strengthened the probability of bullish momentum signals.

## Tools Used

- Statistical analysis
- Decision theory models
- Data visualization
- Financial market data analysis

## Applications

- Investment decision support
- Portfolio strategy evaluation
- Risk management in financial markets

## Future Improvements

- Implement the model using Python for automated analysis
- Add machine learning models for return prediction
- Extend analysis to global market indices
