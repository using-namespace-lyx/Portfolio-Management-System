# Portfolio Management System: A Comprehensive Financial Analysis and Trading Platform


## Introduction

Portfolio Management System is a cutting-edge financial analysis and trading platform designed to empower users with the tools they need to make informed decisions in the stock market. Built with a focus on simplicity and efficiency, our platform provides a wide range of features including real-time stock data, automated backtesting of trading strategies, and a user-friendly interface for managing portfolios.

The platform is built on top of powerful technologies such as Python, Streamlit, Backtrader, and Yahoo Finance, ensuring a robust and reliable experience for users. Whether you're a seasoned trader or just starting out, Stock Manager is designed to cater to your needs.

## Features

- **Real-time Stock Data**: Access up-to-date information on stocks from major exchanges around the world.
- **Automated Backtesting**: Test your trading strategies against historical data to evaluate their performance.
- **Portfolio Management**: Add or remove stocks from your portfolio, view your portfolio's performance, and manage your trades efficiently.
- **User-friendly Interface**: Easily navigate through the platform with a clean and intuitive design.
- **Customizable Strategies**: Develop and implement your own trading strategies using our flexible framework.


## Usage

Once the application is running, you can start exploring the features of Stock Manager. Here's a quick guide to get you started:

- **Create Tables**: Use the create Table SQL script to create the tables in the database.
- **Sign In/Register**: Use the "Sign In" or "Register" buttons to log in or create a new account.
- **View Market Data**: Check the current levels of major market indices like NASDAQ, NYSE, and Nifty 50.
- **Manage Portfolio**: Add or remove stocks from your portfolio, view your portfolio's performance, and manage your trades.
- **Backtest Strategies**: Enter your trading strategy code and run backtests to evaluate its performance.

@KTS-o7 and @using-namespace-lyx contributed to this repository
---

**Note**:

- You need to replace the MongoDB URI in the `pages/Analysis.py` file with your own URI to connect to the database.
- You need to have the following as your sql database:
  - Database Name: STOCKMANAGER

```json
{
'user': 'mysql',
'password': 'mysql',
'host': '127.0.0.1',
'port': '3306',
'database': 'STOCKMANAGER',
'raise_on_warnings': True,
}
```
