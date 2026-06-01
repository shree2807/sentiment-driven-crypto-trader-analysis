# Sentiment-Driven Crypto Trader Analysis

## Objective

This project analyzes the relationship between Bitcoin market sentiment and trader performance using historical trading data and the Fear & Greed Index. The goal is to identify patterns in profitability, trading activity, and trader behavior under different market sentiment conditions.

## Datasets

### 1. Historical Trader Data
- 211,224 trading records
- Fields include account, execution price, trade size, side, and closed PnL

### 2. Bitcoin Fear & Greed Index
- 2,644 sentiment records
- Categories:
  - Extreme Fear
  - Fear
  - Neutral
  - Greed
  - Extreme Greed

## Methodology

1. Data cleaning and quality assessment
2. Timestamp conversion and date alignment
3. Dataset merging using daily dates
4. Feature engineering:
   - Daily PnL
   - Win Rate
   - Trade Frequency
   - Average Trade Size
   - Long/Short Distribution
5. Sentiment-based performance analysis
6. Trader segmentation analysis

## Key Findings

- Extreme Greed periods generated the highest average profitability and win rates.
- Fear periods recorded the highest trading activity.
- Infrequent traders achieved higher average profitability than frequent traders.
- Higher win rates did not always translate into higher profitability.

## Strategy Recommendations

### Strategy 1
Increase participation during Extreme Greed conditions while maintaining strict risk controls.

### Strategy 2
Focus on high-conviction opportunities during Fear periods and avoid excessive trading activity.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repository Structure

```text
charts/
data/
notebooks/
Insights_Report.pdf
```
