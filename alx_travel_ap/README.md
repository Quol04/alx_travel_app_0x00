# ALX Travel App

A Django-based travel application for managing travel listings, bookings, and related services. This project is  designed to demonstrate backend development skills using Django.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Running Tests](#running-tests)

---

## Features

- User authentication and management
- Travel listings management
- Booking system
- Admin interface for managing data
- Extensible for additional travel-related features

---

## Project Structure

```
manage.py
requirements.txt
alx_travel_app/
    __init__.py
    asgi.py
    celery.py
    settings.py
    urls.py
    wsgi.py
listings/
    __init__.py
    admin.py
    apps.py
    models.py
    tests.py
    views.py
    migrations/
```

- `alx_travel_app/`: Main Django project configuration.
- `listings/`: Django app for travel listings and related logic.

---

## Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd alx_travel_app
   ```
2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On Unix or MacOS
   source venv/bin/activate
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```
5. **Create a superuser (optional, for admin access):**
   ```bash
   python manage.py createsuperuser
   ```
6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```
---

## Usage

- Access the app at `http://127.0.0.1:8000/` after starting the server.
- Use the Django admin at `http://127.0.0.1:8000/admin/` for managing listings and users.

---

## Running Tests

To run the test suite:

```bash
python manage.py test
```


