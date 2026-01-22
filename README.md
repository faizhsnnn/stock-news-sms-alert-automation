# 📈 Stock News SMS Alert Automation (Python)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Challenge](https://img.shields.io/badge/Challenge-90DaysOfCode-orange)

---

## 📌 Overview

The Stock News SMS Alert Automation is a Python-based script that monitors daily stock price movements and sends SMS alerts with relevant news headlines when significant changes are detected.

The project integrates multiple external APIs to fetch stock market data and related news, then delivers real-time notifications using Twilio. It was developed as part of my **#90DaysOfCode** journey to strengthen automation and API-driven application skills.

---

## 🚀 Key Features

📊 Daily stock price monitoring using Alpha Vantage API  

📉 Percentage-based price change detection  

📰 Automatic news retrieval using NewsAPI  

📨 SMS alerts with stock movement indicators  

🔗 Integration of multiple external services  

⚙️ Clean and readable automation logic  

---

## 📁 Project Structure
```
stock-news-sms-alert-automation/
│
├── main.py
│ └── Core stock tracking, news fetching, and SMS alert logic
│
└── README.md
└── Project documentation
```

---

## 🛠️ Application Workflow

1. Fetches daily stock price data for a selected company.

2. Calculates the percentage difference between recent closing prices.

3. Determines whether the change exceeds a predefined threshold.

4. Fetches the latest related news articles if the threshold is met.

5. Sends SMS alerts containing stock movement and news headlines.

6. Repeats the process whenever the script is executed.

This project demonstrates real-world automation that combines financial data with live news delivery.

---

## ▶️ Execution Instructions

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/stock-news-sms-alert-automation.git
cd stock-news-sms-alert-automation
```

---

### 2️⃣ Install Dependencies
```
pip install requests twilio
```

---

### 3️⃣ Configure API Credentials (IMPORTANT)

Update the following values in `main.py`:

```
STOCK_API_KEY = "your_alpha_vantage_api_key"
NEWS_API_KEY = "your_newsapi_key"
TWILIO_SID = "your_twilio_account_sid"
TWILIO_TOKEN = "your_twilio_auth_token"
Also configure phone numbers:

from_ = "your_twilio_number"
to = "your_personal_number"
```
---
# ⚠️ Note:
Do not commit real API keys or credentials to public repositories.

Environment variables are recommended for production use.

---
4️⃣ Run the Script
```
python main.py
```

---
# ⚠️ Important Notes
Python 3.x is required

Internet connection is required

Alpha Vantage API has request rate limits

Twilio account must have SMS permissions enabled

Intended for educational and personal automation use

---
# 🧠 Concepts Demonstrated
API consumption and JSON parsing

Data comparison and percentage calculations

Conditional automation logic

Integration of multiple external services

Notification-based automation using Twilio

---
# 🎯 Project Significance

This project demonstrates how Python can be used to automate financial monitoring and alert systems. It reflects real-world use cases such as market tracking, news aggregation, and instant notifications—commonly used in fintech and data-driven applications.

---
# 👨‍💻 Author
Faiz Hasan
BCA Final Year — Graphic Era University

🚀 Python Learner | #90DaysOfCode

---
*“Automation turns market data into actionable insight.”*
