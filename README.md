# Collaborative Investment Platform

This project provides a platform for collaborative investments in stocks and cryptocurrencies. It allows users to search for assets, make investments, create collaborative investment requests, track portfolios, and display data with technical indicators. The app uses **Streamlit**, **Plotly**, and various APIs (such as **Tiingo** for stock data and **CoinCap** for cryptocurrency data) for real-time data fetching and visualization.

## Features

- **Login/Signup**: Users can create accounts and log in to track their investments.
- **Stock and Cryptocurrency Search**: Users can search for stocks or cryptocurrencies using real-time data from Tiingo and CoinCap.
- **Portfolio Management**: Users can view their stock and crypto portfolios, see total investment value, and track performance over time.
- **Collaborative Investments**: Users can initiate and accept collaborative investment requests, where multiple users contribute to a combined investment.
- **Charts and Analysis**: Real-time stock/crypto data charts, historical data with technical indicators (SMA, EMA, RSI), and news sentiment analysis are available.
- **Watchlist**: Users can maintain a watchlist of stocks and cryptocurrencies for easy tracking.
- **Pending Requests**: Users can view and accept pending collaborative investment requests.

## Technologies Used

- **Python**: Programming language used for backend logic.
- **Streamlit**: Used for building the interactive web interface.
- **Pandas**: Data manipulation and analysis.
- **Plotly**: Interactive charts for stock/crypto data visualization.
- **Requests**: Fetches real-time data from external APIs.
- **TextBlob**: Sentiment analysis of news articles.
- **Tiingo API**: Used for fetching stock market data.
- **CoinCap API**: Used for fetching cryptocurrency market data.
- **CSV**: Used for saving user and collaborative request data.

## Installation

### Step 1: Clone the repository

```bash
git clone https://github.com/yourusername/collaborative-investment.git
cd collaborative-investment 
