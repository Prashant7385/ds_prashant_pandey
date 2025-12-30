# Trader Behavior vs Market Sentiment

This project analyzes how trader performance and risk behavior change under Fear and Greed market conditions using Hyperliquid trading data and Bitcoin Fear & Greed Index.

## Project Structure

```
ds_prashant_pandey/
├── notebook_1.ipynb          # Primary analysis notebook
├── notebook_2.ipynb          # Optional additional analysis
├── csv_files/                # All data files
│   ├── daily_trader_metrics.csv
│   ├── historical_data.csv
│   └── fear_greed_index.csv
├── outputs/                  # Visual outputs and results
│   └── pngs/                 # Charts and graphs
├── ds_report.pdf             # Final summarized insights
└── README.md                 # This file
```

## Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn

## Key Insights

- Greed periods show higher leverage and volume
- Fear periods show improved win-rates

## Getting Started

1. Open `notebook_1.ipynb` in Google Colab
2. Load data from `csv_files/` directory
3. Run analysis and generate visualizations
4. Save outputs to `outputs/pngs/` directory
5. Document final findings in `ds_report.pdf`

## Data Sources

- **Hyperliquid Trading Data**: Daily trader metrics and historical data
- **Bitcoin Fear & Greed Index**: Market sentiment indicators
