# Algorithmic-Trading-using-Python
This project implements and backtests 50-day/200-day simple moving-average (SMA) crossover strategies on Apple (AAPL) stock data. It generates both a long/short crossover strategy and a long-bias variant, shifts signals to avoid look-ahead bias, calculates returns, and visualizes performance.It includes:

- Fetches historical daily price data for AAPL from Yahoo Finance using `yfinance`.
  
- Calculates 50-day and 200-day SMAs on closing prices.
  
- Generates trading signals for a long/short crossover and a long-only (no shorts) variant.
   
- Shifts signals by one day to eliminate look-ahead bias.
  
- Computes daily returns, strategy returns, and cumulative returns for both strategies and buy-and-hold.
   
- Plots price series with SMAs and overlays cumulative performance vs. buy-and-hold.  

This project demonstrates how simple technical indicators can be coded, backtested, and visualized in Python to evaluate trading strategy effectiveness.
