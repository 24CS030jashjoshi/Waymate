🚗 WayMate – Smart Ride-Sharing Platform

A full-stack, role-based ride-sharing web application that enables users to seamlessly switch between Driver and Rider roles using a single account. WayMate focuses on affordability, safety, and scalability while promoting eco-friendly transportation.

🌟 Features
🔐 Authentication & Role Management
Secure JWT-based authentication
Single account with Driver ↔ Rider role switching
Centralized USER database for login/signup

🚗 Driver Module
Create and manage rides
View and respond to ride requests
Manage vehicle details
License verification system
View ride history and upcoming rides
Track CO₂ contribution

🧍 Rider Module
Search rides based on location and time
Book rides and send requests
View ride & payment history
Postpaid payment system
SOS emergency feature

🔔 Additional Features

Real-time notifications
Role-based dashboards
Clean and responsive UI
Scalable architecture


🏗️ System Architecture
User
  ↓
Frontend (React + Tailwind)
  ↓
Backend API (Node.js + Express)
  ↓
Databases:
  - USER DB (Authentication)
  - DRIVER DB (Driver Data)
  - RIDER DB (Rider Data)

    
🛠️ Tech Stack
Frontend
React.js (Vite)
Tailwind CSS
React Router
Backend
Node.js
Express.js
Database
MongoDB
Tools & Integration
JWT (Authentication)
Axios (API calls)
Map API (for location features)

🔄 Workflow
User signs up / logs in
Authentication via USER DB
User selects role (Driver / Rider)
Redirected to role-specific dashboard
Perform actions:
Driver → Create ride
Rider → Search & book ride
Ride completion → Payment → History

🚀 Installation & Setup
# Clone the repository
git clone https://github.com/24CS030jashjoshi/waymate.git

# Navigate to project folder
cd waymate

# Install frontend dependencies
cd client
npm install
npm run dev

# Install backend dependencies
cd server
npm install
npm start

📌 Future Scope
Mobile application (Android/iOS)
AI-based ride matching
Real-time GPS tracking
Online payment integration (UPI, cards)
Smart city integration

⚠️ Challenges Faced
Designing dual-role system with single account
Managing multiple databases (USER, DRIVER, RIDER)
Handling role-based authentication and routing
Integrating frontend with backend APIs

🎯 Project Objectives
Reduce travel cost through ride-sharing
Promote eco-friendly transportation
Ensure user safety and trust
Build a scalable and flexible system

📚 References
React.js Documentation
Node.js & Express Docs
MongoDB Docs
Google Maps API
GeeksforGeeks & W3Schools

👨‍💻 Author
Jash Joshi
📧 jashjoshi84@gmail.com
🔗 GitHub: https://github.com/your-username
