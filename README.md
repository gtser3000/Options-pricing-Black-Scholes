Black-Scholes Option Pricing Notebook
Overview
This notebook demonstrates the use of the Black–Scholes model for pricing European call and put options. It also includes data visualization techniques to analyze market option prices and compare them with theoretical prices derived from the model. The notebook is designed to work with Apple (AAPL) stock data fetched using the yfinance library.

Features
Data Fetching:

Retrieves historical stock prices for AAPL.
Fetches the nearest expiration options chain (calls and puts).
Black–Scholes Pricing Model:

Implements the Black–Scholes formula for European options.
Accounts for spot price, strike price, time to maturity, risk-free rate, volatility, and dividend yield.
Cross-Sectional Analysis:

Compares market option prices to Black–Scholes prices.
Visualizes discrepancies between market and model prices.
3D Surface Plot:

Visualizes the relationship between option prices, strike prices, and time to expiration using a 3D surface plot.
Prerequisites
Python 3.8+
Required libraries: yfinance, pandas, numpy, matplotlib
How to Use
Install the required libraries if not already installed:


pip install yfinance pandas numpy matplotlib
Run the notebook cells sequentially to:

Fetch stock and options data.
Calculate Black–Scholes prices.
Perform cross-sectional analysis.
Generate visualizations.
Modify the configuration parameters (e.g., TICKER, RISK_FREE, DIV_YIELD) as needed to analyze other stocks or scenarios.

Outputs
Summary Statistics: Key metrics such as last close price, number of options, and expirations.
Plots:
Call mid-price vs. strike for the nearest expiration.
Market vs. Black–Scholes prices.
3D surface plot of option prices.
Notes
Ensure that the yfinance library is up-to-date to avoid API issues.
The notebook includes error handling for missing or incomplete data.
License
This notebook is provided for educational purposes and is not intended for financial or investment advice.
