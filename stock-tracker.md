# 📈 Stock Tracker & Alert System (MVP)

## 🚀 Project Overview
Build a web-based **Stock Tracker and Alert System** using Python that allows users to track stock prices, monitor performance, and receive alerts based on predefined conditions.

The system should provide real-time or near real-time stock data and enable users to manage their personal watchlists.

---

## 🎯 Objective
Develop a scalable MVP that:
- Allows users to track selected stocks
- Provides meaningful insights (price changes, trends)
- Supports alerting mechanisms
- Demonstrates strong backend, API integration, and data handling

---

## 👥 User Roles

### 1. User
- Register/Login using Google
- Manage personal watchlist
- Set alerts
- View stock data and trends

---

## 🧩 Core Features

### 🔐 1. Authentication (Google OAuth)
- Login using Google account
- Secure session handling
- Each user has isolated data (watchlist, alerts)

---

### 📊 2. Stock Data Integration
- Integrate with stock APIs (choose one):
  - Yahoo Finance (yfinance)
  - Alpha Vantage
  - Finnhub
- Fetch:
  - Current price
  - Daily change (% and absolute)
  - Historical data (for charts)

---

### ⭐ 3. Watchlist Management
- Add stocks to watchlist
- Remove stocks
- View all tracked stocks
- Show:
  - Current price
  - % change
  - Day high/low

---

### 🔔 4. Alert System
Users can set alerts such as:
- Price above X
- Price below Y
- % change exceeds threshold

System should:
- Continuously check conditions (via background job)
- Trigger alert when condition is met

---

### 📩 5. Notifications
- Email notifications (mandatory)
- Optional: webhook / in-app notification

---

### 📈 6. Stock Details Page
- Historical price chart (last 1 month / 3 months / 1 year)
- Key metrics:
  - Open / Close
  - High / Low
  - Volume

---

### 📊 7. Dashboard
- User’s watchlist summary
- Top gainers / losers (optional)
- Alerts triggered recently

---

## 🛠️ Tech Stack

### Backend
- Python (FastAPI preferred)

### Database
- MySQL

### ORM
- SQLAlchemy

### Frontend
- React (preferred)  
  or any modern frontend framework

### Authentication
- Google OAuth 2.0

### Background Jobs
- Celery / FastAPI background tasks / cron jobs

---

## 🏗️ System Requirements

- RESTful API design
- Modular project structure
- Environment-based configuration (.env)
- Proper error handling
- Input validation
- Logging for alerts and jobs

---

## 🧪 Testing Requirements

- Unit tests are mandatory
- Use `pytest`
- Cover:
  - Business logic (alerts, calculations)
  - API endpoints
- Mock external APIs (stock data providers)
- Ensure tests run via a single command

---

## 📦 Deliverables

- ✅ Complete source code (GitHub repository)
- ✅ API documentation (Swagger / Postman)
- ✅ Unit tests with instructions
- ✅ README with setup instructions
- ✅ Sample data / mock setup
- ✅ Screenshots or demo video

---

## ⚙️ Bonus Features (Optional)

- Portfolio tracking (add quantity, track P&L)
- Advanced indicators (RSI, moving averages)
- Telegram / WhatsApp alerts
- Real-time updates using WebSockets
- Multi-market support (US + India)

---

## 📌 Evaluation Criteria

- Code quality & structure
- API integration handling
- Test coverage and quality
- Alert system reliability
- UI usability
- Documentation clarity

---

## 🎯 Expected Outcome

A functional stock tracking application that:
- Allows users to monitor stocks efficiently
- Provides actionable alerts
- Demonstrates backend, API integration, and system design skills

---
