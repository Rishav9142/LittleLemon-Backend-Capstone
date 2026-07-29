# Meta Back-End Developer Capstone

## Overview

This project is the final capstone for the **Meta Back-End Developer Professional Certificate** on Coursera.

The application is built using **Django** and **Django REST Framework** and provides REST APIs for managing restaurant menu items and table bookings. It also includes user authentication, MySQL database integration, and unit tests.

---

## Technologies Used

- Python
- Django
- Django REST Framework
- MySQL
- Djoser Authentication
- Token Authentication
- Git & GitHub

---

## Features

- User registration and authentication
- Menu Management API
- Table Booking API
- Django Admin Panel
- MySQL Database
- RESTful API implementation
- Unit Tests
- Insomnia/Postman compatible

---

# API Endpoints

## Authentication

```
POST /auth/users/
POST /auth/token/login/
POST /auth/token/logout/
```

---

## Menu API

```
GET    /api/menu/items/
POST   /api/menu/items/

GET    /api/menu/items/<id>/
PUT    /api/menu/items/<id>/
PATCH  /api/menu/items/<id>/
DELETE /api/menu/items/<id>/
```

---

## Booking API

```
GET    /api/booking/tables/
POST   /api/booking/tables/

GET    /api/booking/tables/<id>/
PUT    /api/booking/tables/<id>/
PATCH  /api/booking/tables/<id>/
DELETE /api/booking/tables/<id>/
```

---

## Running the Project

Clone the repository

```bash
git clone https://github.com/Rishav9142/LittleLemon-Backend-Capstone.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run migrations

```bash
python manage.py migrate
```

Start the development server

```bash
python manage.py runserver
```

---

## Peer Review

The project satisfies the following requirements:

- Django serves web pages
- Git version control
- MySQL database integration
- Menu API
- Table Booking API
- User Registration & Authentication
- Unit Tests
- API can be tested using Insomnia or Postman

---

## Repository

GitHub Repository:

https://github.com/Rishav9142/LittleLemon-Backend-Capstone