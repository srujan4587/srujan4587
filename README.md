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

#### Step 2: Set up a virtual environment

'''bash
python3 -m venv .venv
source .venv/bin/activate  # For Mac/Linux
.venv\Scripts\activate     # For Windows

Step 3: Install dependencies
bash
Copy code
pip install -r requirements.txt
Step 4: Set up environment variables
Create a .env file in the root directory and add your API keys (for Tiingo and CoinCap).

plaintext
Copy code
TIINGO_API_KEY=your_tiingo_api_key
COINCAP_API_KEY=your_coincap_api_key
Step 5: Run the app
bash
Copy code
streamlit run app.py
The app will run locally at http://localhost:8501/.

Usage
Login or Sign Up: When the app starts, you'll be prompted to either sign up for a new account or log in to an existing one.
Search for Stocks or Cryptos: Navigate to the Home tab where you can search for stocks or cryptocurrencies by name or symbol.
Make an Investment: Once you select an asset, you can view its real-time data and make an investment using the virtual balance.
Collaborative Investments: Navigate to Collaborative Investments, where you can create a request to invest together with other users. You can contribute to a shared investment by specifying the amount.
Portfolio and Watchlist: You can view your investments and manage your watchlist for stocks and cryptocurrencies in the Portfolio and Watchlist tabs.
File Structure
bash
Copy code
/collaborative-investment
    ├── app.py               # Main application logic
    ├── requirements.txt     # Required Python packages
    ├── data/
    │   ├── users.csv        # Stores user data (username, password)
    │   ├── collab_requests.csv  # Stores collaborative investment requests
    │   └── portfolio.csv    # Stores user portfolio data
    ├── assets/              # Stores static assets like images (if any)
    └── .env                 # Contains environment variables (API keys)
API Integrations
Tiingo API (Stocks)
Tiingo API is used to fetch stock market data. You need a valid API key to use it. You can sign up for a free account on Tiingo to get your API key.

Tiingo API
CoinCap API (Cryptocurrency)
CoinCap API is used to fetch cryptocurrency market data. You can use the public API without an API key, but a registered API key is recommended for rate-limiting purposes.

CoinCap API

