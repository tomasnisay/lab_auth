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
1. Initialize an Express.js project:
   ```bash
   npm init -y
   npm install express mysql2 jsonwebtoken bcrypt dotenv
