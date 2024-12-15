# OKAE Stock Market Simulator

## Project Description

The OKAE Stock Market Simulator is an interactive Python application that simulates a stock market environment where users can view stock prices, invest in stocks, track a portfolio, and even view detailed candlestick charts for each stock. The simulation generates random stock price data for a predefined set of stocks and allows users to manage their investments, buy/sell stocks, and visualize stock price movements over time. 

This project demonstrates how to simulate stock market behavior, manage a user's portfolio, and use visualizations like bar charts and candlestick charts to analyze stock price data.

## Features

1. Simulate stock market prices for a set of stocks.
2. View current stock prices and choose stocks to invest in.
3. Track a portfolio of investments and manage it (buy/sell stocks).
4. Sort stocks by price.
5. View detailed candlestick charts for each stock.
6. Real-time simulation of stock prices with periodic updates.

## Setup Instructions

### Prerequisites

Ensure you have Python 3.x installed. You will also need to install the following Python libraries:
- `random` (included in Python by default)
- `time` (included in Python by default)
- `matplotlib`
- `pandas`
- `plotly`

### Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/okae-stock-market-simulator.git
   cd okae-stock-market-simulator
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scriptsctivate`
   ```

3. Install the required dependencies:
   ```bash
   pip install matplotlib pandas plotly
   ```

4. Run the simulation:
   ```bash
   python stock_market_simulator.py
   ```

## Usage Examples

### 1. **Viewing Stocks**

When prompted, choose option `1` to view available stocks and their current prices.

Example:
```bash
1. View Stocks
2. Invest in a Stock
3. View Portfolio
4. Sort Stocks by Price
5. Show Candlestick Chart
6. Sell a Stock
7. Exit
Enter your choice: 1

Available Stocks:
Apple: $120.45
Google: $102.35
Amazon: $150.22
Microsoft: $140.20
Tesla: $125.80
```

### 2. **Investing in Stocks**

Choose option `2` to invest in a stock. After selecting a stock, enter the amount you'd like to invest.

Example:
```bash
Choose a stock to invest in: 1
Enter the amount to invest in Apple: $1000
You invested $1000.00 in Apple at $120.45.
```

### 3. **Viewing Portfolio**

Choose option `3` to view your portfolio, which lists all stocks you've invested in.

Example:
```bash
Your Portfolio:
Stock: Apple, Invested: $1000.00, Buy Price: $120.45
```

### 4. **Sorting Stocks by Price**

Choose option `4` to sort stocks by their current price.

Example:
```bash
Stocks sorted by price:
Amazon: $150.22
Microsoft: $140.20
Tesla: $125.80
Apple: $120.45
Google: $102.35
```

### 5. **Viewing a Candlestick Chart**

Choose option `5` to view a candlestick chart for a stock in your portfolio.

Example:
```bash
Your Investments:
1. Apple

Choose a stock to view its candlestick chart: 1
```

The application will display a candlestick chart using Plotly.

### 6. **Selling Stocks**

Choose option `6` to sell a stock from your portfolio. You'll see the profit or loss from the sale.

Example:
```bash
Your Portfolio:
1. Apple

Choose a stock to sell: 1
You sold Apple at $125.80.
Profit: $105.29
```

### 7. **Exiting the Application**

To exit the application, choose option `7` from the main menu.

Example:
```bash
Exiting...
```

## Contributing

Feel free to fork this repository and contribute to the development of this stock market simulator. You can submit bug reports, feature requests, or pull requests with improvements.

## License

This project is licensed under the MIT License.
.md…]()


Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
