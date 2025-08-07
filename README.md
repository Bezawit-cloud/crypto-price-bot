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

1. **Clone the repository**

   ```bash
   git clone <your-repo-url>
   cd <your-project-folder>
   Create a .env file in the project root folder and add your bot token and chat ID:

ini
Copy
Edit
BOT_TOKEN=your_telegram_bot_token
CHAT_ID=your_telegram_chat_id
Create a .gitignore file in the project root (if not already present) and add:

bash
Copy
Edit
.env
Install the required packages

bash
Copy
Edit
pip install -r requirements.txt
Run the bot script

bash
Copy
Edit
python bot.py
Usage

The bot collects price data every minute.

Use the Telegram bot to receive price alerts.

You can manually trigger alerts or set up scheduling for automatic checking.

Notes
Never share your .env file publicly.

To run the bot 24/7, consider deploying it on a cloud server or VPS.
"# crypto-price-bot" 
