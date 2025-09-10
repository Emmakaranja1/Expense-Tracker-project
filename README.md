# 💰 Expense Tracker

A full-stack Expense Tracker application built with **Next.js (frontend)**, **Flask + SQLAlchemy (backend)**, and **PostgreSQL (database)**.  
It allows users to register, log in, and manage their personal expenses with authentication support.

---

## 🚀 Tech Stack

### Frontend
- [Next.js 13+ (App Router)](https://nextjs.org/)
- TypeScript + React Hooks
- TailwindCSS (for styling)
- JWT authentication

### Backend
- [Flask](https://flask.palletsprojects.com/)
- Flask-SQLAlchemy (ORM)
- Flask-Migrate (database migrations)
- Flask-CORS (CORS handling)
- JWT for authentication

### Database
- PostgreSQL

---


---

## ⚙️ Setup Instructions

### 1. Clone Repo
```bash
git clone https://github.com/yourusername/Expense-Tracker-project.git
cd Expense-Tracker-project


Backend Setup

cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt




Create .env file in backend/
DATABASE_URL=postgresql://user:password@localhost:5432/expense_db
SECRET_KEY=your_secret_key


Run migrations:
flask db init
flask db migrate -m "Initial migration"
flask db upgrade

Start server:
python app.py




3. Frontend Setup
cd frontend
npm install


Create .env.local in frontend/:

NEXT_PUBLIC_API_URL=http://localhost:5000/api


Run frontend:

npm run dev


Frontend runs at: http://localhost:3000

🔑 Features

User registration (email + password, JWT auth)

User login/logout

Token storage in localStorage

Expense CRUD (to be added)

Dashboard for tracking expenses (coming soon)

🗄 Database Schema
Users
Table users {
  id          int [pk, increment]
  email       varchar(120) [unique, not null]
  password    varchar(200) [null]   // nullable for Google login
  provider    varchar(50) [default: 'email']
  google_id   varchar(200) [unique]
  created_at  timestamp [default: now()]
}


(Expenses & Budgets tables will be added later)

🛠 Roadmap

✅ Email/password auth

⏳ Google OAuth

⏳ Expense & budget management

⏳ Reports & analytics dashboard

⏳ Deployment (Render + Vercel)

🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you’d like to change.

📜 License

MIT License © 2025 Your Name




