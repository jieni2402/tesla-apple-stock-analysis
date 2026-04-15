# Tesla vs Apple: Risk and Return Analysis

A Python-based analysis comparing Tesla and Apple stock performance using return, volatility, Sharpe ratio, and rolling volatility.

## 1. Problem & User
This project compares Tesla (TSLA) and Apple (AAPL) to evaluate their performance in terms of return, risk, and risk-adjusted return.  
The target users are retail investors and finance students who want a simple and clear comparison of two well-known stocks.

## 2. Data
The data were collected from the Alpha Vantage API and saved locally as a CSV file for reproducibility.  
Key fields include daily closing prices of Tesla and Apple.  
Access date: April 14, 2026

## 3. Methods
Python is used to perform data loading, cleaning, and analysis.  
The main steps include:
- Loading data from CSV using pandas  
- Calculating daily returns  
- Computing cumulative return, volatility, and Sharpe ratio  
- Visualising results using matplotlib  

## 4. Key Findings
- Apple had a higher cumulative return (-3.09% vs Tesla's -13.82%) during the period
- Tesla showed higher volatility (37.40% vs Apple's 21.54%), indicating higher risk
- Apple achieved a better Sharpe ratio (-0.36 vs Tesla's -0.88), meaning better return per unit of risk
- Rolling volatility shows Tesla's risk remained consistently higher than Apple's throughout the period

## 5. How to Run
1. Install required packages if needed:
   pip install pandas matplotlib alpha_vantage
2. Ensure the file TSLA_AAPL_data.csv is in the same folder
3. Open the notebook and run all cells

## 6. Limitations & Future Work
- The analysis is based only on historical price data  
- External factors such as market conditions are not included  
- Future work may include more companies or additional indicators  
