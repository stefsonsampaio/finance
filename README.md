# Finance Web App - Buy and Sell Stocks

Welcome to our **Finance Web App**, a platform that allows you to buy and sell stocks, manage your portfolio, and track stock prices in real-time. This web application is built using Python with the Flask framework, and it leverages the CS50 Library for database interactions. The application is designed to handle user authentication, stock quotes retrieval, and stock transaction management.

## Prerequisites

Before running the application, ensure you have the following:

1. Python installed on your system.
2. The required Python libraries: `cs50`, `flask`, and `flask_session`. You can install them using `pip`.

## Getting Started

1. Clone the repository to your local machine.
2. Make sure you set the environment variable `API_KEY` with your API key to retrieve real-time stock prices.

## Features

### 1. Register and Login

Users can **register** for a new account and **log in** securely. Passwords are hashed and stored for enhanced security.

### 2. Stock Quote

The app allows users to enter a stock symbol and get the latest **real-time** stock information, including the name and current price.

### 3. Buy Stocks

Users can **buy stocks** by entering the stock symbol and the number of shares they wish to purchase. The app checks for available cash and updates the user's portfolio and cash balance accordingly.

### 4. Sell Stocks

**Selling stocks** is easy! Users can select the stock from their portfolio and specify the number of shares to sell. The app will update the portfolio and cash balance accordingly.

### 5. Portfolio Management

The app provides a **real-time view** of the user's current stock portfolio. It displays the stock symbol, name, price, and the total number of shares owned for each stock. The total portfolio value, including cash, is also displayed.

### 6. Transaction History

Users can view a **history of their stock transactions**, including buy and sell actions. The history shows the type of transaction, stock symbol, price, number of shares, and the timestamp.

## Setup and Usage

1. Set your API key as an environment variable:

export API_KEY=your_api_key_here

2. Run the Flask application:

flask run

3. Open your web browser and navigate to `http://127.0.0.1:5000` to access the Finance Web App.

**Please Note:** This app is built for educational purposes and uses a simulated stock market. It does not involve real money. The stock quotes are fetched from a real-time stock quote API.

Feel free to explore and enhance the app to suit your needs or integrate it into your financial projects. Happy investing! 📈🚀
