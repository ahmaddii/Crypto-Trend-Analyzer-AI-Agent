# 📈 Crypto Trend Analyzer AI Agent

An AI-powered crypto monitoring agent built using **n8n**, **OpenAI**, **Gmail SMTP**, and **Google Sheets**. This agent runs every hour to fetch live cryptocurrency prices, analyzes market signals with GPT-4, sends email alerts, and logs the data into a Google Sheet — all fully automated.

---

## 🚀 Features

- ⏰ **Hourly Automation** using Schedule Trigger
- 📉 **Real-Time Crypto Data** via HTTP Request to CoinGecko
- 🤖 **AI-Powered Market Insight** with OpenAI (ChatGPT/GPT-4)
- 📩 **Email Alerts** using Gmail SMTP
- 📊 **Data Logging** in Google Sheets for tracking

---

## 📂 Files in this Repo

| File                          | Description                               |
|-------------------------------|-------------------------------------------|
| `Crypto_Trend_Analyzer.json` | n8n Workflow file — import into n8n       |
| `README.md`                  | This documentation                        |
| `.env.example`               | Example of required environment variables *(optional)*

---

## 🛠️ Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/ahmaddii/Crypto-Trend-Analyzer-AI-Agent.git
cd Crypto-Trend-Analyzer-AI-Agent
