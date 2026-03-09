# Flask Authentication System

A modern **Flask authentication project** that demonstrates how to
implement a complete user authentication flow using Flask and related
libraries.

This project includes **user registration, login, logout, session
management, password hashing, and a protected dashboard**.

------------------------------------------------------------------------

## Features

-   User Registration (`/register`)
-   User Login (`/login`)
-   User Logout (`/logout`)
-   Protected Dashboard (`/dashboard`)
-   Session management using **Flask‑Login**
-   Secure password hashing using **Werkzeug**
-   Flash messages for user feedback
-   Clean UI using **HTML, CSS, and Google Fonts**
-   SQLite database using **SQLAlchemy**

------------------------------------------------------------------------

## Technologies Used

-   Python
-   Flask
-   Flask-Login
-   Flask-SQLAlchemy
-   Flask-Migrate
-   SQLite
-   HTML / CSS

------------------------------------------------------------------------

## Project Structure

    flask_auth_app/
    │
    ├── app/
    │   ├── __init__.py
    │   ├── extensions.py
    │   ├── models/
    │   │   └── user.py
    │   ├── routes/
    │   │   ├── auth.py
    │   │   └── main.py
    │   ├── templates/
    │   │   ├── base.html
    │   │   ├── register.html
    │   │   ├── login.html
    │   │   └── dashboard.html
    │   └── static/
    │       └── style.css
    │
    ├── config.py
    ├── run.py
    ├── requirements.txt
    └── README.md

------------------------------------------------------------------------

## Installation

Clone the repository:

``` bash
git clone https://github.com/your-username/flask-auth-system.git
cd flask-auth-system
```

Create a virtual environment:

``` bash
python -m venv .venv
```

Activate the environment:

Windows (Git Bash):

``` bash
source .venv/Scripts/activate
```

Install dependencies:

``` bash
pip install -r requirements.txt
```

------------------------------------------------------------------------

## Run the Application

Start the Flask application:

``` bash
python run.py
```

Then open your browser and go to:

    http://127.0.0.1:5000

------------------------------------------------------------------------

## How to Test

1.  Go to **/register** and create a new account.
2.  Login from **/login**.
3.  Access the protected **/dashboard** page.
4.  Logout using **/logout**.
5.  Try opening `/dashboard` without logging in --- it will redirect you
    to login.

------------------------------------------------------------------------

## Security Features

-   Passwords are securely hashed using **Werkzeug**
-   Authentication handled by **Flask‑Login**
-   Protected routes using `@login_required`
-   User session management

------------------------------------------------------------------------

## Learning Purpose

This project was built as part of a **Flask training Task** to
practice:

-   Authentication systems
-   Flask project structure
-   Database integration
-   Session management