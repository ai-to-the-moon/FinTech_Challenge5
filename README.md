# Financial Planning Tools

This Jupyter notebook uses information from the Free Crypto API and the API from the Alpaca SDK to calculate present values of crypto, stock, and bond portfolios and estimate if the portfolio values are enough to sustain an emergency fund or enough to retire on. 

This is a challenge assignment from Rice's FinTech Bootcamp program due on July 14, 2022. The purpose of this assignment is to demonstrate our knowledge using APIs and MCForecastTools.py (for MonteCarlo Simulations) and apply it to a real world scenario. 

## Technologies

This program is written in Python (3.7.13) and developed using JupyterLabs notebooks using Windows. We are importing the os, requests, json (2.0.9), pandas (1.1.5), dotenv, alpaca_trade_api (2.3.0), matplotlib (3.1.1), and datetime libraries (see parenthesis for versions used in program development).

## Installation Guide

Downloading the code & associated files using `git clone` from the repository is sufficient to download the program, ensure that the associated libaries (see Technologies section) are installed on your machine as well. If there are any issues with the library functions please refer to the versions used for app development (see Technnologies section for this information as well).  Please note that this is a Jupyter notebook. 

If you'd like to run this code on your computer, ensure that the you create a .env file in the root of the program to assign your Alpaca API keys. A "sample.env" file is included in this folder for you. 

## Usage

This notebook is using a reference portfolio that has a crypto wallet with 1.2 bitcoin (`btc_coins`) and 5.3 ethereum (`eth_coins`) and a stock and bond portfolio with 100 shares of SPY (SPDR S&P 500 ETF Trust) (`spy_shares`) and 200 shares of AGG (iShares Core US Aggregate Bond ETF) (`agg_shares`).

## APIs

The Free Crypto API is used to pull the current values of Bitcoin and Ethereum and Alpaca's SDK API is used to pull the closing price values of AGG and SPY from the previous trading day. 

## MCForecastTools.py

MCForecastTools.py is a python file that's used for the Monte Carlo Simulation calculations. 

Example Histogram
![Histogram](Images/5-4-monte-carlo-histogram.png)

Example Line Plot
![Line Plot](Images/5-4-monte-carlo-line-plot.png)

## Contributors

Project contributors are the Rice FinTech bootcamp program team (instructor Eric Cadena) who developed the tasks for this project along with myself (Paula K) who's written the code in the workbook.
