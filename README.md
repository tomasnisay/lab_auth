# Lab Authentication API

## Description
This project demonstrates how to implement authentication using **Express.js**, **MySQL**, and **JWT**. It includes signup, login, logout, and protected profile endpoints, tested with Postman. The project also highlights the importance of password hashing and token-based security.

## Author
Tomas Nisay

## Tech Stack
- Express.js  
- MySQL  
- JWT (JSON Web Token)  
- Bcrypt  
- Postman  

## Features
- User signup with password hashing  
- User login with JWT authentication  
- User logout  
- Protected profile endpoint requiring valid token  

## Installation
1. Install dependencies:
   ```bash
   npm init -y
   npm install express mysql2 jsonwebtoken bcrypt dotenv
2. Set up a MySQL database and users table.
3. Configure environment variables in a .env file (DB credentials, port, JWT secret).

## Usage
   -POST /auth/signup → Register a new user
   -POST /auth/login → Authenticate and receive JWT
   -POST /auth/logout → End session (invalidate token on client-side)
   -GET /profile → Access protected profile data with valid JWT

## Notes
   -Password hashing ensures user credentials are stored securely.
   -JWT provides token-based authentication (sign, verify, expiry).
   -Postman is used to test success and error cases for all endpoints.
   -This project is a practical lab for understanding authentication workflows.
