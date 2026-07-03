# 🥗 Nutrition Assistant

A Full Stack MERN application that helps users maintain a healthy lifestyle through personalized nutrition recommendations, meal planning, calorie tracking, and diet management.

---

# Project Overview

Nutrition Assistant is designed to simplify healthy eating by allowing users to manage their meals, calculate daily calorie intake, receive personalized diet recommendations, and monitor nutritional progress. The application combines a responsive React frontend with a secure Node.js and Express backend connected to MongoDB.

---

# Features

- User Registration & Login
- Secure JWT Authentication
- User Dashboard
- Meal Planner
- Daily Calorie Tracker
- BMI Calculator
- Nutrition Recommendation
- Personalized Diet Plans
- Food Database
- User Profile Management
- Responsive Design

---

# Tech Stack

## Frontend

- React.js
- Bootstrap
- HTML5
- CSS3
- JavaScript
- Axios
- React Router

## Backend

- Node.js
- Express.js
- REST API
- JWT Authentication

## Database

- MongoDB
- Mongoose ODM

---

# Project Structure

```
Nutrition-Assistant/

│

├── client/

│   ├── public/

│   ├── src/

│   │

│   ├── components/

│   ├── pages/

│   ├── services/

│   ├── App.js

│   └── index.js

│

├── server/

│   ├── config/

│   ├── controllers/

│   ├── middleware/

│   ├── models/

│   ├── routes/

│   ├── services/

│   ├── app.js

│   └── server.js

│

├── package.json

├── README.md

└── .env

```

---

# System Architecture

```
React Frontend
       |
       V
Express REST API
       |
       V
Business Logic Layer
       |
       V
Mongoose ODM
       |
       V
MongoDB Database
       |
       V
Nutrition APIs (Optional)
```

---

# Main Modules

### Authentication

- Register
- Login
- JWT Token
- User Profile

### Nutrition Module

- Food Search
- Nutrition Analysis
- Calorie Tracking
- Meal Planning

### Dashboard

- Daily Calories
- Nutrition Summary
- Progress Tracking

### User Management

- Update Profile
- Change Password
- Preferences

---

# REST APIs

## Authentication

POST /api/users/register

POST /api/users/login

GET /api/users/profile

PUT /api/users/profile

---

## Meals

POST /api/meals

GET /api/meals

PUT /api/meals/:id

DELETE /api/meals/:id

---

## Nutrition

POST /api/nutrition/calculate

GET /api/nutrition/recommendation

GET /api/foods

---

# Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Nutrition-Assistant.git
```

## Install Frontend

```bash
cd client
npm install
```

## Install Backend

```bash
cd server
npm install
```

## Environment Variables

Create a .env file

```
PORT=5000

MONGO_URI=your_mongodb_connection

JWT_SECRET=your_secret_key
```

## Run Backend

```bash
npm start
```

## Run Frontend

```bash
npm start
```

---

# Technologies Used

- MongoDB
- Express.js
- React.js
- Node.js
- Mongoose
- JWT
- Bootstrap
- Axios
- HTML
- CSS
- JavaScript

---

# Future Enhancements

- AI Diet Recommendation
- Nutrition Chatbot
- Barcode Scanner
- Health Reports
- Fitness Tracker Integration
- Mobile Application
- Dark Mode
- Admin Dashboard

---

# Advantages

- Secure Authentication
- Easy to Use
- Responsive Design
- Personalized Nutrition Plans
- Meal Tracking
- Calorie Monitoring
- Scalable Architecture
- Fast Performance

---

