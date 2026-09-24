# Smart Expense Tracker 💰

A web-based expense management application built with **Python, Flask, SQLite, and SQLAlchemy**.  
The application allows users to securely manage their expenses, organize them into categories, and view spending through a dashboard.

## 🚀 Features

- User Registration & Login
- Secure password hashing
- Add, edit, and delete expenses
- Create and manage expense categories
- Category-wise expense analysis
- Interactive expense chart
- Personalized dashboard
- Spending suggestions
- User-specific expense management
- Logout functionality

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **Database:** SQLite
- **ORM:** Flask-SQLAlchemy
- **Authentication:** Flask-Login
- **Security:** Werkzeug Password Hashing
- **Frontend:** HTML, CSS, Bootstrap
- **Charts:** Chart.js

## 📂 Project Structure

```text
SmartExpenseTracker/
│
├── app.py
├── models.py
├── database.db
│
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── add_expenses.html
│   ├── edit_expenses.html
│   ├── categories.html
│   ├── add_category.html
│   └── edit_category.html
│
└── README.md
