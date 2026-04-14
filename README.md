# Tesla vs Apple: Risk and Return Analysis

A Python-based analysis comparing Tesla and Apple stock performance using return, volatility, and Sharpe ratio.

## 1. Problem & User
This project compares Tesla (TSLA) and Apple (AAPL) to evaluate their performance in terms of return, risk, and risk-adjusted return.  
The target users are retail investors and finance students who want a simple and clear comparison of two well-known stocks.

## 2. Data
The data were collected from the Alpha Vantage API and saved locally as a CSV file for reproducibility.  
Key fields include daily closing prices of Tesla and Apple.  
Access date: [please fill in]

## 3. Methods
Python is used to perform data loading, cleaning, and analysis.  
The main steps include:
- Loading data from CSV using pandas  
- Calculating daily returns  
- Computing cumulative return, volatility, and Sharpe ratio  
- Visualising results using matplotlib  

## 4. Key Findings
- Tesla shows higher cumulative returns but also higher volatility  
- Apple provides more stable performance  
- Apple has better risk-adjusted return (higher Sharpe ratio)  
- Tesla’s risk fluctuates more significantly over time  

## 5. How to Run
1. Install required packages if needed:
   pip install pandas matplotlib alpha_vantage
2. Ensure the file `tesla_apple_prices.csv` is in the same folder
3. Open the notebook and run all cells

## 6. Limitations & Future Work
- The analysis is based only on historical price data  
- External factors such as market conditions are not included  
- Future work may include more companies or additional indicators  
