# Binance Futures Testnet Trading Bot

## Setup

1. Clone repo
2. Install dependencies:
   pip install -r requirements.txt

3. Add .env:
   API_KEY=your_key
   API_SECRET=your_secret

## Run

### Market Order
python -m bot.cli --symbol BTCUSDT --side BUY --type MARKET --quantity 0.001

### Limit Order
python -m bot.cli --symbol BTCUSDT --side SELL --type LIMIT --quantity 0.001 --price 60000

## Features
- Market & Limit orders
- CLI input validation
- Logging
- Error handling

## Assumptions
- Testnet account is active
- API keys are valid
