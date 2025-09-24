# 💸 Expense Tracker (Full Stack)

A full-stack expense tracker application built with **Next.js** on the frontend and **Node.js/Express** (or Flask/Python) on the backend, with a PostgreSQL (or MongoDB) database.  
This app helps users manage personal finances by tracking expenses, categories, and budgets.





## 🚀 Features

- ✅ User authentication (register & login)
- ✅ Add, edit, and delete expenses
- ✅ Categorize expenses (Food, Rent, Transport, etc.)
- ✅ Monthly/weekly expense summary
- ✅ Responsive UI (Next.js + Tailwind CSS / CSS Modules)
- ✅ REST API backend with JWT authentication
- ✅ Database storage for persistence (PostgreSQL or MongoDB)
- ✅ Charts & analytics for spending insights



## 🛠️ Tech Stack

### Frontend
- [Next.js](https://nextjs.org/) (React framework)
- Context API / Redux Toolkit (state management)
- Tailwind CSS or CSS Modules (styling)
- Chart.js / Recharts (data visualization)

### Backend
- Node.js + Express (or Flask + Python)
- REST API with JWT authentication
- PostgreSQL (via Prisma / Sequelize / SQLAlchemy) or MongoDB (via Mongoose)



## 📂 Project Structure

Expense-Tracker-project/
├── backend/ # Express or Flask backend
│ ├── src/
│ │ ├── models/ # Database models
│ │ ├── routes/ # API routes
│ │ ├── controllers/ # Logic for routes
│ │ └── server.js # App entry point
│ └── package.json
│
├── frontend/ # Next.js frontend
│ ├── app/ # App Router pages
│ ├── components/ # Reusable components
│ ├── context/ # State management
│ └── package.json
│
├── README.md



## ⚙️ Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/Emmakaranja1/Expense-Tracker-project.git
cd Expense-Tracker-project
2. Frontend Setup



cd frontend
npm install
npm run dev
Visit 👉 http://localhost:3000

3. Backend Setup
If using Node.js + Express:



cd backend
npm install
npm run dev
Runs API server at 👉 http://localhost:5000

If using Flask (Python):


Copy code
cd backend
pip install -r requirements.txt
flask run
Runs API server at 👉 http://127.0.0.1:5000