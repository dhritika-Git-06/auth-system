Authentication System Project

Project Overview
This project is a basic Authentication System that allows users to register, log in, and access protected resources.
It demonstrates how user authentication works in real-world applications using backend logic, APIs, and a database.

This project focuses on backend development and core computer science concepts rather than UI design.

Objectives

Implement user registration

Implement user login

Secure user passwords

Authenticate users using tokens

Protect routes from unauthorized access

Core Concepts Used

Authentication
The process of verifying the identity of a user.

Authorization
The process of allowing or denying access to specific resources after authentication.

Password Hashing
Passwords are never stored in plain text. They are converted into hashed values before saving to the database.

JWT (JSON Web Token)
A token-based authentication method used to securely identify logged-in users.

API
The system exposes endpoints that allow frontend or external services to interact with the backend.

Technologies Used

Python

FastAPI

SQLite (or MySQL / PostgreSQL)

SQLAlchemy

JWT

Passlib (for password hashing)

Project Features

User Registration
Users can create an account by providing a username, email, and password.
Passwords are hashed before storing in the database.

User Login
Users can log in using valid credentials.
On successful login, a JWT access token is generated.

Protected Routes
Certain API routes can only be accessed by authenticated users with a valid token.

Database Integration
User data is stored securely in a relational database.

Project Workflow

User sends registration request

Password is hashed

User data is saved in the database

User logs in with credentials

Server verifies credentials

JWT token is issued

Token is used to access protected routes

Project Structure

auth-system
main.py
database.py
models.py
schemas.py
auth.py
requirements.txt
README
LICENSE

How to Run the Project

Create a virtual environment

Install dependencies

Run the FastAPI server

Test APIs using Swagger UI or Postman

Why This Project Is Important for Interviews

Demonstrates backend fundamentals

Shows understanding of security practices

Covers databases, APIs, and authentication

Common real-world system asked in interviews

Possible Enhancements

Role-based access control

Refresh tokens

Email verification

Password reset feature

Frontend integration

Author
Dhritika Sahu
Computer Science Student

License
This project is licensed under the MIT License.
