# 💸 Expense Tracker App

A full-stack expense tracker built with **Next.js (frontend)**, **Flask (backend)**, and **PostgreSQL**.  
Helps users manage expenses, track budgets, and gain spending insights.

---

## 📌 Features

### ✅ Core
- JWT authentication
- Add, edit, delete expenses
- Categories (Food, Transport, Bills, Entertainment, etc.)
- Dashboard with charts (daily/weekly/monthly)
- Budget setting & alerts
- Dark/light mode

### 🚀 Advanced (Future)
- Recurring expenses (subscriptions, rent, etc.)
- Multiple wallets/accounts (cash, bank, M-Pesa, card)
- Export reports (CSV, PDF, Excel)
- AI-powered insights
- Shared/group expenses
- Cloud sync & reminders

---

## 🏗️ Tech Stack
- **Frontend**: Next.js, React, TailwindCSS, Chart.js  
- **Backend**: Flask (Python), JWT Auth  
- **Database**: PostgreSQL + SQLAlchemy/Prisma ORM (if applicable)  
- **Deployment**: Vercel (frontend), Render/Heroku (backend), Supabase/Neon (Postgres)

---

## 📂 Structure
expense-tracker/
│── README.md # Root project README
│── frontend/ # Next.js frontend
│ └── README.md
│── backend/ # Flask + Postgres backend
│ └── README.md



---

## 🚀 Getting Started

### Prerequisites
- Node.js (>=18)  
- Python (>=3.10)  
- PostgreSQL (local or cloud: Supabase/Neon)  
- npm or yarn, pip or pipenv  

### Setup
# Clone repo
git clone https://github.com/yourusername/expense-tracker.git
cd expense-tracker


Install dependencies
# Frontend
cd frontend && npm install

# Backend
cd backend && pip install -r requirements.txt



Environment variables

Copy .env.example → .env in both frontend and backend.

Run apps
# Backend
cd backend && flask run

# Frontend (new terminal)
cd frontend && npm run dev



🛠️ Deployment

Frontend → Vercel

Backend → Render

Database → postgres


📜 License

MIT
