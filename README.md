# Crypto Price Alert Bot

This project is a Python-based tool that automates cryptocurrency price monitoring and alerts via Telegram.

## Features

- Fetches cryptocurrency price data every 1 minute using API calls and timestamps.
- Cleans and processes data using Pandas.
- Provides visualizations of price trends.
- Implements a Telegram bot that sends price alerts when the price crosses a set threshold.
- Currently, alerts are sent manually; scheduling for automatic alerts is possible.

## Requirements

- Python 3.x
- pandas
- python-dotenv
- python-telegram-bot (or your preferred Telegram bot library)
- requests (for API calls)
- matplotlib or seaborn (for visualization)

## Setup & Usage

## 1 Clone the repository
``bash
   git clone <your-repo-url>
   cd <your-project-folder>
## 2 Create a .env File
Inside your project folder, create a .env file with the following contents:

BOT_TOKEN=your_telegram_bot_token
CHAT_ID=your_telegram_chat_id
API_KEY=your_coin_api_key  # (if applicable)
Note: This file is used to keep your sensitive information (like bot token and chat ID) safe and should not be pushed to GitHub.
##  3 Add .env to .gitignore
Make sure your .gitignore file includes:
.env
## 4 Install Required Packages
Install all required Python libraries using:
Install Required Packages
pip install -r requirements.txt
## Usage
Once everything is set up, run the bot script with:
python bot.py
## ✅ Tips
-Make sure your .env file is correctly named and in the same directory as your script.

-If your token or chat ID are showing in your code or GitHub, remove them immediately, regenerate if necessary, and commit a cleaned version.


"# crypto-price-bot" 
"# crypto-price-bot" 
"# crypto-price-bot" 
