# HRMS Lite (Django)

A lightweight Human Resource Management System (HRMS Lite) built with **Django** and a simple HTML/JavaScript frontend. This application allows an admin to manage employees and track daily attendance through a clean, professional, and easy-to-use web interface.

This project is designed to demonstrate end-to-end full-stack development skills including:

- RESTful API design  
- Database modeling with Django ORM  
- Server-side validation and error handling  
- Frontend UI with meaningful states  
- Modular and readable code structure  

---

## Features

### Employee Management
The admin can:
- Add a new employee with:
  - Employee ID (unique)
  - Full Name
  - Email Address (validated)
  - Department  
- View all employees in a table  
- Delete an employee  

###Attendance Management
The admin can:
- Mark attendance for an employee with:
  - Date  
  - Status (Present / Absent)  
- View attendance records for a specific employee  

---

##Tech Stack

### Backend:
- Python 3.9+
- Django 4.x
- SQLite (default database)
- REST-style APIs (without Django REST Framework for simplicity)

### Frontend:
- HTML  
- CSS (simple, clean UI)  
- Vanilla JavaScript (fetch API)

---

##  Project Structure
hrms_lite_django/
│
├── manage.py
├── requirements.txt
│
├── hrms_lite/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
│
└── core/
├── models.py
├── views.py
├── urls.py
├── migrations/
└── templates/
└── index.html


##  Installation & Setup

### Step 1 — Clone or Extract the ZIP
If provided as a ZIP, extract it and navigate into the project folder.

### Step 2 — Install Dependencies

###pip install -r requirements.txt
Step 3 — Setup Database

Run migrations:

python manage.py makemigrations core
python manage.py migrate

Step 4 — Run the Server
python manage.py runserver

Step 5 — Open in Browser

Visit:

http://127.0.0.1:8000/


