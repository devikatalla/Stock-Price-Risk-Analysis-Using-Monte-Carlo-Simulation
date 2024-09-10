# Stock Risk Analysis using Monte Carlo Simulation

This project performs stock risk analysis using Monte Carlo simulation to predict the potential future prices of stocks based on historical data. It aims to help investors understand the expected returns, potential risks, and price volatility of stocks. The analysis covers various metrics like mean and median future prices, as well as the 5th and 95th percentile projections to capture worst- and best-case scenarios.

The goal of this project is to assess the risk and return associated with stocks from the technology sector, using historical price data and Monte Carlo simulations. This method provides insights into the range of possible future outcomes for stock prices, helping to make informed investment decisions by quantifying potential gains and losses.

# Technologies Used
- **Python**: Core programming language used for data analysis and simulations.
- **NumPy**: Used for numerical operations, especially for handling large datasets and random number generation.
- **Pandas**: Used for data manipulation and handling stock price data.
- **Matplotlib**: Used to visualize the results of the Monte Carlo simulation, including plots of potential stock price paths and distributions.
- **SciPy**: Used for statistical operations like calculating normal distributions.
- **Yahoo Finance (yfinance)**: Used to fetch historical stock price data for the chosen companies.

# Methodology
1. **Data Collection**: Stock price data for companies such as AAPL, MSFT, AMZN, GOOG, and META is collected using the yfinance library.
2. **Returns Calculation**: Historical daily returns are calculated from the closing prices.
3. **Monte Carlo Simulation**: A Monte Carlo simulation is performed to generate future stock price paths over a defined period based on historical return statistics.
4. **Risk Analysis**: The simulation provides key metrics like expected final prices, expected profit or loss, and price percentiles (5th and 95th) to evaluate downside risks and upside potentials.
5. **Visualization**: The results of the simulation are visualized using line plots and histograms to show potential future price distributions.

# Example Results
## For Meta (META) Stock:
- **Mean Final Price**: $506.01
- **Median Final Price**: $505.79
- **5th Percentile Final Price**: $486.10
- **95th Percentile Final Price**: $526.13
- **Expected Profit or Loss (Mean)**: $1.22
- **Expected Profit or Loss (Median)**: $1.00
- **5th Percentile Profit or Loss**: $-18.69
- **95th Percentile Profit or Loss**: $21.34
