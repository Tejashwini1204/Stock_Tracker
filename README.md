# Stock Tracker

A Django-based stock tracking web application that fetches stock market data using the Alpha Vantage API and displays stock price information for different time periods.

## Project Overview

The application allows users to enter a stock symbol and view market data for different time frames.

The application currently supports:

- Daily stock data
- Weekly stock data
- Monthly stock data
- Stock symbol selection
- Open, High, Low, and Close price data

## Key Features

### Stock Symbol Selection

Users can enter a stock symbol, such as `IBM`, to retrieve stock market data.

### Time Frame Selection

The application supports:

- 1 Day
- 1 Week
- 1 Month

### Market Data

The application retrieves Open, High, Low, and Close values using the Alpha Vantage API.

### Data Visualization

Retrieved stock data is passed to the Django template for visualization.

## Technologies

- Python
- Django
- Requests
- Alpha Vantage API
- HTML
- CSS
- JavaScript

## Project Structure

```text
Stock_Tracker/
├── kothaed/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── stocky/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   ├── migrations/
│   ├── static/
│   └── templates/
├── manage.py
└── requirements.txt

git clone https://github.com/Tejashwini1204/Stock_Tracker.git
cd Stock_Tracker

pip install django requests

python manage.py runserver
