# Astrology App 🌟

## Features
- Daily Rashi Fal
- Tarot Reading Booking
- Kundali Astrology Booking
- Remedies Store + Astrology Mart
- Payment Integration (Razorpay)

## Tech Stack
- Backend: Django REST Framework
- Frontend: Flutter / React
- Database: PostgreSQL
- Payments: Razorpay
- Notifications: Firebase Cloud Messaging (FCM)

## Setup
```bash
git clone https://github.com/USERNAME/astrology-app.git
cd astrology-app
---

### **2️⃣ Docker & docker-compose Setup (Django + Postgres + Redis)**

**Folder structure बनाओ:**
astrology-app/
│
├── backend/
│   ├── Dockerfile
│   ├── requirements.txt
│   ├── manage.py
│   ├── config/
│   │    ├── __init__.py
│   │    ├── settings.py
│   │    ├── urls.py
│   │    └── wsgi.py
│   ├── apps/
│   │    ├── __init__.py
│   │    └── (your Django apps here)
│   ├── .env.example
│
├── docker-compose.yml
├── README.md
├── .gitignore
