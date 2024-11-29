
# Investment Platform

This project provides a platform for collaborative investments in stocks and cryptocurrencies. It allows users to search for assets, make investments, create collaborative investment requests, track portfolios, and display data with technical indicators. The app uses **Streamlit**, **Plotly**, and various APIs (such as **Tiingo** for stock data and **CoinCap**, **Cryptopanic** for cryptocurrency data) for real-time data fetching and visualization.

## Features

- **User Authentication**: Secure login and registration system for managing portfolios and investments.
- **Real-Time Data Fetching**: Integration with external APIs for live stock and cryptocurrency data.
- **Portfolio Management**: View and manage investment portfolios with detailed information on holdings.
- **Investment Transactions**: Buy and sell stocks and cryptocurrencies with real-time portfolio updates.
- **Historical Data Visualization**: Display historical price data with charts and graphs for analysis.
- **Watchlist Feature**: Add stocks and cryptocurrencies to a watchlist for easy tracking.
- **Collaborative Investments**: Initiate and accept collaborative investment requests with other users.
- **Pending Requests Management**: View and manage pending collaborative investment requests.
- **Investment Breakdown Visualization**: See a breakdown of contributions and investment status after acceptance.
- **Sentiment Analysis Visualization**: Display sentiment analysis results in a pie chart format, providing insights into market sentiment based on news data.
- **Responsive Design**: User-friendly and responsive design for a seamless experience across devices.
## Technologies Used


- **Python**: The primary programming language used for backend development.
- **Streamlit**: A framework for building interactive web applications in Python.
- **Pandas**: A data manipulation and analysis library for handling data in DataFrames.
- **NumPy**: A library for numerical computations in Python.
- **Matplotlib**: A plotting library for visualizing data.
- **Plotly**: A graphing library for creating interactive plots and visualizations.
- **TextBlob**: A library for processing textual data, used for sentiment analysis.
- **CSV**: A module for reading and writing CSV files for data storage.
- **Requests**: A library for making HTTP requests to fetch live data from external APIs.
- **APIs**: Integration with external APIs for real-time and historical investment data.


## Installation

### Step 1: Clone the repository

```bash
git clone https://github.com/yourusername/collaborative-investment.git
cd collaborative-investment
```

### Step 2: Set up a virtual environment
Create a virtual environment to isolate your project's dependencies. Run the following commands based on your operating system:

For Mac/Linux:
```bash
python3 -m venv .venv
source .venv/bin/activate
```
For Windows:
```bash
python3 -m venv .venv
.venv\Scripts\activate
```

### Step 3: Install dependencies
Install the required Python packages using pip:

```bash
pip install -r requirements.txt
```

### Step 4: Run the app
Now, you can run the Streamlit app using the following command:

```bash
streamlit run app.py
```

## Usage


- **Login or Sign Up**: When the app starts, you'll be prompted to either sign up for a new account or log in to an existing one.
- **Search for Stocks or Cryptos**: Navigate to the Home tab where you can search for stocks or cryptocurrencies by name or symbol.
- **Make an Investment**: Once you select an asset, you can view its real-time data and make an investment using the virtual balance.
- **Portfolio and Watchlist**: You can view your investments and manage your watchlist for stocks and cryptocurrencies in the Portfolio and Watchlist tabs.
- **Collaborative Investments**: Navigate to Collaborative Investments, where you can create a request to invest together with other users. You can contribute to a shared investment by specifying the amount.

