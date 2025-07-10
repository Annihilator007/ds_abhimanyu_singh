# ds_abhimanyu_singh
Analysis of the trader behavior and market sentiment.

# Web3 Trading Team - Data Science Assignment

## Overview
This project explores how trader behavior aligns or diverges from market sentiment using:
- Bitcoin Fear & Greed Index
- Historical trades from Hyperliquid

## Folder Structure

ds_abhimanyu_singh/
├── notebook_1.ipynb
├── csv_files/
│ ├── fear_greed_index.csv
│ └── historical_data.csv
├── outputs/
│ ├── profitability_by_sentiment.png
│ ├── trade_volume_by_sentiment.png
│ └── leverage_proxy_by_sentiment.png
├── ds_report.pdf
└── README.md


## Key Insights
- Greed phases have higher profitability.
- Traders adjust positions more aggressively during Extreme Fear.
- Sentiment shifts influence trading side (BUY/SELL) tendencies.

## Setup Instructions
1. Upload datasets under `csv_files/`
2. Open and run `notebook_1.ipynb` in Google Colab
3. Outputs are saved under `outputs/`
4. Final summary is in `ds_report.pdf`

## Recommendations
- Include market sentiment as a model feature.
- Design trading strategies responsive to sentiment shifts.
- Use leverage cautiously during fearful periods.
