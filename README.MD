# TelegramCurrencyWorthBot

A Telegram bot that provides real-time currency and cryptocurrency prices.

## Features
- Get the latest cryptocurrency prices using commands like `/price_btc`.
- Supports multiple cryptocurrencies, including Bitcoin (BTC), Ethereum (ETH), and many more.
- Fetches real-time data from CoinGecko API.
- Basic command support: `/start`, `/help`, `/usd_price`.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AlirezaMz10/Telegram-Currency-Worth-Bot.git
   cd TelegramCurrencyWorthBot
   ```

2. Set up your Telegram bot:
   - Get a bot token from [BotFather](https://t.me/botfather) on Telegram.
   - Replace `YOUR_BOT_TOKEN` in `main()` with your actual token.

## Usage
Run the bot using:
```bash
python main.py
```

Then, use the following commands in Telegram:
- `/start` - Start the bot
- `/help` - Get help message
- `/usd_price` - Check a predefined USD price
- `/price_<symbol>` - Get the price of a cryptocurrency (e.g., `/price_btc` for Bitcoin)

## API Source
This bot fetches real-time cryptocurrency data from [CoinGecko API](https://www.coingecko.com/).

## Contributing
Pull requests are welcome! If you have any suggestions, feel free to open an issue.

## License
This project is licensed under the MIT License.

