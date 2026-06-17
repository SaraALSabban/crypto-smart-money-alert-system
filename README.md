# crypto-smart-money-alert-system


An advanced n8n automation workflow that monitors cryptocurrency market activity, analyzes liquidity and trading volume, detects potential accumulation or distribution patterns, and sends real-time Telegram alerts.

---

## 📌 Overview

This workflow automatically scans selected crypto assets using the DexScreener API and applies a custom Smart Money scoring algorithm to identify strong market signals.

The system filters weak or suspicious activity, classifies market behavior, and delivers formatted alerts to subscribers.

---

## ⚙️ Workflow Architecture

```
Cron Scheduler
       ↓
Generate Token List
       ↓
DexScreener API
       ↓
Market Data Processing
       ↓
Smart Money Detection Algorithm
       ↓
Signal Strength Filtering
       ↓
Subscriber Database
       ↓
Telegram Alert System
```

---

## ✨ Features

- ⏱ Automated market monitoring every 50 minutes
- 📊 Real-time crypto market data analysis
- 🧠 Custom Smart Money scoring algorithm
- 📈 Volume and liquidity evaluation
- 🔍 Accumulation and distribution detection
- 🗃 Subscriber management using PostgreSQL
- 📩 Automated Telegram notifications
- 🔄 Fully automated n8n workflow

---

## 🛠 Technologies Used

- n8n
- JavaScript
- REST APIs
- DexScreener API
- PostgreSQL
- Telegram Bot API

---

## 📂 Project Structure

```
crypto-smart-money-alert-system/
│
├── README.md
├── crypto-smart-money-alert-system.json
└── workflow-screenshot.png
```

---

## 📥 Import Workflow

1. Download the JSON workflow file.
2. Open your n8n instance.
3. Select **Import Workflow**.
4. Configure your own:
   - PostgreSQL connection
   - Telegram Bot credentials
5. Activate the workflow.

---

## 💡 Technical Highlights

This project demonstrates:

- Automation architecture design
- API integration and data processing
- Custom JavaScript logic inside n8n Code nodes
- Database querying and subscriber management
- Automated notification systems
- Workflow optimization and filtering logic

---

## 📄 License

This repository is shared as a portfolio project to demonstrate software engineering and automation skills.
