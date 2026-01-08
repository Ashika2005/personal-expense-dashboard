# 💸 Personal Finance Tracker (Django)

A simple and intuitive **Django-based web application** to manage your personal finances.  
Track your transactions, categorize them as income or expense, view savings, set financial goals, and monitor progress — all in one place.

---

## 🚀 Features

### ✅ User Authentication
- Secure user registration and login
- Each user has private, user-specific data

### 💰 Transaction Management
- Add transactions as **Income** or **Expense**
- Categorize transactions for better organization
- View transaction history

### 📊 Dashboard Overview
- Total Income
- Total Expenses
- Net Savings calculation

### 🎯 Goal Tracking
- Create financial goals (e.g., *Buy a Laptop*)
- Track progress toward target amount
- Visual progress indicators

### 🔐 User-Specific Data
- Transactions and goals are linked to individual users
- Data isolation using Django authentication system

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS (Django Templates)
- **Database:** SQLite (default, configurable)
- **Authentication:** Django built-in auth system

---

## 📦 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/personal-expense-dashboard.git
cd expense-tracker-django
### 2️⃣ Create a Virtual Environment
``` bash
python -m venv venv
3️⃣ Activate the Virtual Environment

Windows

venv\Scripts\activate


Mac / Linux

source venv/bin/activate

4️⃣ Install Dependencies
pip install -r requirements.txt

5️⃣ Run Migrations
python manage.py migrate

6️⃣ Start the Development Server
python manage.py runserver


Open your browser and visit:

http://127.0.0.1:8000/


