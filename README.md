# AZURE-DBMS-PROJECT-2025
A simple, cloud-ready Inventory Management System built with Flask, PostgreSQL, and Bootstrap, deployed on Azure App Service. Designed for hands-on learning and practical experience with an industry-relevant tech stack.
Awesome! Here's a suggested structure for your GitHub README, and I’ll also outline how we can scaffold the project.

---

# 📦 Inventory Management System

A simple, cloud-ready Inventory Management System built with **Flask**, **PostgreSQL**, and **Bootstrap**, deployed on **Azure App Service**. Designed for hands-on learning and practical experience with an industry-relevant tech stack.

---

## 🚀 Tech Stack

- **Backend**: Flask (Python)
- **Database**: PostgreSQL (hosted on Azure)
- **Frontend**: Bootstrap (color-coded, modern UI)
- **Deployment**: Azure App Service
- **Version Control**: Git & GitHub

---

## 🎯 Features

- Add, edit, and delete inventory items (name, quantity, price).
- Visual stock indicators:
  - 🟢 **Green**: Quantity ≥ 20
  - 🟠 **Orange**: Quantity < 20
  - 🟡 **Yellow**: Quantity < 5
  - 🔴 **Red**: Quantity = 0
- Manual input only (no file uploads).
- **Soft Delete**: Mark as inactive (hidden from UI).
- **Hard Delete**: Fully remove from database.
- Azure deployment with PostgreSQL cloud-hosted DB.
- Clean Git workflow (clear, descriptive commit messages).

---

## 📚 Learning Objectives

- Master core concepts of Flask web development.
- Learn PostgreSQL database management (CRUD operations).
- Build a responsive UI using Bootstrap.
- Deploy a Flask app with a managed PostgreSQL instance on Azure.
- Follow real-world Git workflow practices.

---

## 🛠️ Project Setup

### Prerequisites

- Python 3.x
- PostgreSQL (local setup for development)
- Git & GitHub account
- Azure account (for deployment)

---

### 🏗️ Initial Project Structure

```
inventory-management/
├── app/
│   ├── __init__.py
│   ├── routes.py
│   ├── models.py
│   ├── static/
│   │   └── custom.css
│   └── templates/
│       └── index.html
├── .gitignore
├── config.py
├── requirements.txt
├── run.py
└── README.md
```

---

### 📝 Steps to Start

1. **Git Setup**
   - Initialize Git repo and push to GitHub
   - Follow clear commit message practices

2. **Flask App Setup**
   - `__init__.py` to initialize Flask app + SQLAlchemy
   - `routes.py` for route handling (CRUD)

3. **Database Setup**
   - Use SQLAlchemy with PostgreSQL URI (no SQLite)
   - Define `Item` model with soft delete flag

4. **UI Setup**
   - Bootstrap-integrated `index.html`
   - Color-coded table rows based on quantity

5. **Deploy to Azure**
   - Azure App Service for the Flask app
   - Azure PostgreSQL flexible server for DB

---

## 📌 Notes

- No authentication (single-user system)
- Focused on educational value (no shortcuts)
- Azure environment variables for secure DB connection

---

---
