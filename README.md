# 📊 CryptoAlertBot

A Telegram bot that monitors real-time cryptocurrency prices and notifies you the moment your target price is hit.

Built with Python as part of my Backend Developer journey.

---

## ✨ Features

- 🔔 **Real-time price alerts** — Get notified the moment a coin reaches your target
- 💰 **30+ supported coins** — BTC, ETH, SOL, DOGE and many more
- 👤 **Per-user alerts** — Each user manages their own independent alerts
- 🗂️ **Alert management** — View and delete your active alerts at any time
- 🔒 **Secure** — API keys handled with environment variables

---

## 🤖 Commands

| Command | Description |
|---|---|
| `/start` | Start the bot |
| `/info` | Show available commands and supported coins |
| `/alert BTC 80000` | Set an alert for when BTC reaches $80,000 |
| `/my_alerts` | View your active alerts |
| `/delete_alerts` | Delete all your alerts |

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Library:** python-telegram-bot
- **API:** [CoinCap API v3](https://docs.coincap.io/)
- **Environment:** python-dotenv

---

## 🚀 How to Run

1. Clone the repo
```bash
git clone https://github.com/yourusername/Crypto-Alert-Bot
cd Crypto-Alert-Bot
```

2. Install dependencies
```bash
pip install python-telegram-bot requests python-dotenv
```

3. Create a `.env` file with your credentials
```
TELEGRAM_TOKEN=your_telegram_bot_token
API_KEY=your_coincap_api_key
```

4. Run the bot
```bash
python main.py
```

---

## 📌 Supported Coins

BTC, ETH, SOL, BNB, XRP, ADA, DOGE, DOT, MATIC, LTC, AVAX, LINK, UNI, ATOM, XLM, ALGO, VET, FIL, TRX, ETC, HBAR, SAND, MANA, AAVE, GRT, EOS, THETA, NEO, EGLD, FTM

---

## 👨‍💻 Author

Developed by **BenjaminMontenegro16** as part of my Backend Developer journey.

[![X](https://img.shields.io/badge/X-@BenjaMon__Dev-black?logo=x)](https://twitter.com/BenjaMon_Dev)
