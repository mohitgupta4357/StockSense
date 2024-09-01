# StockSense

## Introduction
This project offers a comprehensive portfolio management and optimization system based on Modern Portfolio Theory. By analyzing historical stock data, it calculates key financial metrics and determines optimal portfolio allocations to maximize risk-adjusted returns.

## Key Features
- Retrieves stock data via Yahoo Finance API
- Computes daily returns and moving averages
- Generates visualizations for stock performance and correlations
- Applies Modern Portfolio Theory principles
- Creates efficient frontier
- Optimizes portfolio based on Sharpe ratio

## Setup
### Requirements
- Python 3.x
- Libraries: pandas, yfinance, matplotlib, seaborn, numpy

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/mohitgupta4357/StockSense.git
   ```
2. Install dependencies:
   ```
   pip install pandas yfinance matplotlib seaborn numpy
   ```

## How to Use
1. Edit the `tickers` list in the script with your chosen stock symbols.
2. Modify `DAYS` and `AMOUNT` variables as needed.
3. Execute the script:
   ```
   python portfolio_optimization.py
   ```

## Core Components
1. **Data Processing**: Downloads and prepares historical stock data for analysis.
2. **Visualization**: Generates various plots including price trends, moving averages, volume charts, return distributions, and correlation heatmaps.
3. **Portfolio Optimization**: Calculates expected returns and volatility, generates the efficient frontier, and maximizes the Sharpe ratio.
4. **Output**: Provides the efficient frontier plot, optimal portfolio weights, and suggested stock quantities for purchase.

## Understanding the Results
The tool provides:
- Visual insights into stock performance and relationships
- Efficient frontier plot illustrating risk-return tradeoffs
- Optimal portfolio allocation for maximizing the Sharpe ratio
- Recommended stock quantities based on a specified investment amount

## Contribute
We welcome contributions! To contribute:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/NewFeature`)
3. Commit changes (`git commit -m 'Add NewFeature'`)
4. Push to the branch (`git push origin feature/NewFeature`)
5. Submit a Pull Request

## License
This project is under the MIT License. See the [LICENSE](LICENSE) file for full details.

## Important Note
This tool is designed for educational purposes only and should not be considered financial advice. Always conduct thorough research and consult with a qualified financial advisor before making investment decisions.
