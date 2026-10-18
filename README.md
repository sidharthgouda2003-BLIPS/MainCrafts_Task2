# MainCrafts Task 2 – User Authentication System

## Project Overview
This project is a web-based User Authentication System developed using Python and Flask. It allows users to register, log in, access a protected dashboard, and log out securely.

## Technologies Used
- Python
- Flask
- SQLite
- HTML
- Werkzeug Password Hashing

## Features
- User registration
- User login and authentication
- Password hashing for security
- Session management
- Protected user dashboard
- Logout functionality
- SQLite database integration

## Project Structure
```text
MainCrafts_Task2/
├── app.py
├── requirements.txt
├── README.md
├── database.db
├── templates/
│   ├── register.html
│   ├── login.html
│   └── dashboard.html
└── screenshots/
```

## How to Run the Project

1. Install Python.
2. Install the required dependency:

   `python -m pip install -r requirements.txt`

3. Start the Flask application:

   `python app.py`

4. Open a browser and visit:

   `http://127.0.0.1:5000`

## Authentication Flow
1. New users create an account through the registration page.
2. Passwords are stored as hashes in the SQLite database.
3. Registered users log in with their credentials.
4. Authenticated users can access the dashboard.
5. Users can log out to clear their session.

## Conclusion
This project demonstrates the implementation of a basic user authentication system using Flask, SQLite, HTML, and session management.
