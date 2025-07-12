# Zerodha-Assessment

# EMA Crossover Trading Strategy

A Python-based backtesting system for EMA crossover strategy on Indian stocks.

## Quick Start

1. **Install Requirements**
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Script**
   ```bash
   python main.py
   ```

## Strategy Details

- **Method**: 9/21 EMA Crossover
- **Stocks**: 10 NIFTY50 stocks (diversified sectors)
- **Capital**: ₹1,00,000 per stock
- **Period**: Last 3 years

## What You Get

- **Charts**: Price charts with EMA lines and buy/sell signals
- **Metrics**: Sharpe ratio, max drawdown, win rate, etc.
- **Reports**: Individual stock + combined portfolio analysis
- **CSV Files**: All results exported for further analysis

## Key Files

- `main.py` - Main strategy script
- `requirements.txt` - Required Python packages
- `portfolio_performance_summary.csv` - Results summary
- `combined_portfolio_results.csv` - Portfolio data

## Customization

Edit these variables in the script:
```python
EMA_SHORT = 9        # Short EMA period
EMA_LONG = 21        # Long EMA period
INITIAL_CAPITAL = 100000  # Capital per stock
STOCKS = [...]       # Stock list
```
## Output

The script generates:
- Performance charts for each stock
- Combined portfolio visualization
- Detailed performance metrics
- Trade logs and statistics
