# Personal-Expense-Tracker

## Description
A personal expense tracker built with Django and React. It includes user authentication, expense management, a dashboard with reports, and budgeting features.

## Setup Instructions

### Backend (Django)
1. Create a virtual environment and activate it:
   ```bash
     python -m venv venv
     source venv/bin/activate
2. Initialize the django project:
   ```bash
    django-admin startproject expense_tracker
    cd expense_tracker
3. Create the django apps
   ```bash
    python manage.py startapp users
    python manage.py startapp expenses
    python manage.py startapp dashboard
    python manage.py startapp budget
  4. Install dependencies
    ```bash
       pip install djangorestframework django-cors-headers
     
  5. Make migration and create superuser
  ```bash
    python manage.py migrate
    python manage.py createsuperuser

6. Set up frontend
  ```bash
    npx create-react-app frontend
    cd frontend
