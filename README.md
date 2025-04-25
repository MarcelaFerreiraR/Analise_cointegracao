# Brazilian Stock Market Analysis Dashboard

Project Overview
This project provides a comprehensive financial analysis tool for the Brazilian stock market (B3), focusing on technical analysis, pair trading strategies, and market insights. The dashboard fetches real-time data from TradingView and historical data from Yahoo Finance to offer traders and analysts a robust platform for making data-driven investment decisions.
Features

Real-time Stock Data Collection: Automatically scrapes active stocks from TradingView's Brazilian market section
Historical Price Analysis: Downloads and processes historical stock prices using Yahoo Finance API
Advanced Time Series Processing: Organizes data into various time frames (daily, weekly, biweekly, monthly, yearly)
Return Calculation: Computes percentage returns for all stocks in the dataset
Pair Trading Analysis:

Correlation analysis between stock pairs
Beta coefficient calculation
Cointegration testing for identifying statistically related pairs
Spread visualization and analysis
Statistical metrics for pair selection



Technical Stack

Python 3.x for core functionality
Pandas for data manipulation and analysis
BeautifulSoup for web scraping
yfinance for Yahoo Finance API integration
statsmodels for statistical modeling and tests
matplotlib and seaborn for data visualization

# Clone this repository
git clone https://github.com/MarcelaFerreiraR/brazilian-stock-analysis.git

# Navigate to the project directory
cd brazilian-stock-analysis

# Install required packages
pip install pandas requests beautifulsoup4 yfinance statsmodels matplotlib seaborn
