# Tesla vs Apple: Risk and Return Analysis

A Python-based financial analysis comparing the performance of Tesla (TSLA) and Apple (AAPL) using key metrics including return, volatility, Sharpe ratio, and rolling volatility.

## 1. Problem & User

This project evaluates and compares Tesla and Apple in terms of return, risk, and risk-adjusted performance.
It aims to answer three key questions: which stock delivers higher returns, which carries higher risk, and which provides better performance per unit of risk.

The target users are retail investors and finance students who seek a clear and data-driven comparison of two major stocks.

## 2. Data

The dataset consists of daily closing prices for Tesla and Apple.
Data were originally collected from the Alpha Vantage API and then saved locally as a CSV file to ensure reproducibility.

* Data source: Alpha Vantage API
* Access date: April 14, 2026
* Variables: Date, TSLA closing price, AAPL closing price

## 3. Methods

Python is used for data processing, analysis, and visualization.
The main steps include:

* Loading data from a CSV file using pandas
* Cleaning and sorting time-series data
* Calculating daily returns
* Computing key financial metrics:

  * Cumulative return
  * Annualized volatility
  * Sharpe ratio
* Visualising trends and risk using matplotlib

## 4. Key Findings

* Apple achieved a higher cumulative return (-3.09%) compared to Tesla (-13.82%) over the selected period
* Tesla exhibited significantly higher volatility (37.40% vs 21.54%), indicating greater risk
* Apple had a better Sharpe ratio (-0.36 vs -0.88), suggesting stronger risk-adjusted performance
* Rolling volatility analysis shows Tesla consistently remained more volatile than Apple

Overall, Tesla appears to be a higher-risk asset, while Apple demonstrates more stable performance and better risk-adjusted returns.

## 5. How to Run

1. Install required packages if needed:
   pip install pandas matplotlib numpy
2. Ensure the file `TSLA_AAPL_data.csv` is in the same folder as the notebook
3. Open the Jupyter Notebook and run all cells

## 6. Limitations & Future Work

This project has several limitations:

* It relies only on historical price data and does not include fundamental or macroeconomic factors
* The analysis is based on a relatively short time period (100 trading days)
* The risk-free rate is assumed and may not reflect real market conditions

Future improvements could include:

* Extending the time period for analysis
* Including more stocks for comparison
* Incorporating additional financial indicators (e.g., beta, drawdown)
* Integrating macroeconomic or market sentiment data
