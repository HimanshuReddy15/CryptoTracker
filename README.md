# CryptoTracker
Auto_Crypto_API_Data_pulling_Project
Project Goal:

This project aims to collect cryptocurrency price data from the CoinMarketCap API, track price changes over different time intervals, and visualize the data to identify potential trends.

Project Steps:

Data Acquisition: Retrieve real-time price data of the top 15 cryptocurrencies (e.g. Bitcoin, Ethereum) using the CoinMarketCap API.

Data Storage: Append the retrieved data to a CSV file (API.csv) at regular intervals (e.g., every minute) for a specified duration (e.g., 5.5 hours).

Data Processing: Clean, transform, and organize the collected data into a usable format with Pandas dataframes for analysis. This includes calculating average price changes over different time periods.

Visualization: Use Seaborn and Matplotlib to generate informative charts and plots showcasing:

The percentage change of cryptocurrency prices over different timeframes (1h, 24h, 7d, 30d, 60d, 90d).
The historical price trends of Bitcoin.
Key Tools and Libraries:

CoinMarketCap API
Python
Pandas
Requests
Seaborn
Matplotlib
In Essence: This project automates the collection and analysis of cryptocurrency market data to provide visualizations that could inform trading or investment decisions.
