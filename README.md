# 📦 Smart Competitor Price Tracker (n8n)

This is a fully automated price tracker built with [n8n](https://n8n.io) that:

- Monitors 3 competitors
- Scrapes prices daily using ScrapingBee
- Compares with your price (Nike)
- Sends alerts via email if competitor is cheaper
- Logs results to Google Sheets

## 🔧 Setup Instructions

1. Clone this repo
2. Import `price-tracker-workflow.json` into your n8n instance
3. Set up your Google Sheets and ScrapingBee API
4. Customize the schedule, email, and thresholds as needed

## 🧾 Sheets Required

- `Nike`
- `Sporting Goods`
- `Finish Line`
- `Price Tracker Logs`

## 🧠 How It Works

![Workflow](./screenshots/workflow.png)

Each sheet is read → scraped → compared → logged.

## 📩 Alerts

Emails are sent only when competitor price is lower.

---

MIT License
