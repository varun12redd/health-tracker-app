# 🏥 Health Tracker Mobile App

A full-stack mobile application built using **React Native and Node.js** to track and manage patient health records efficiently.

---

## 🚀 Overview

This application allows users to:
- Track patient health data (vitals, symptoms)
- Manage patient records
- Monitor health conditions
- View basic analytics and history

It is built as a **cross-platform mobile app** with a backend API for data management.

---

## ✨ Features

- User authentication (login/signup)
- Add and manage patient details
- Record health data (BP, heart rate, symptoms)
- View patient history and records
- Basic data visualization
- Secure API integration

---

## 🛠️ Tech Stack

### Frontend
- React Native
- Expo
- Context API

### Backend
- Node.js
- Express.js

### Database
- MongoDB

---

## 📁 Project Structure

```bash
health-tracker-app/
│
├── backend/          # Node.js backend (APIs, DB, auth)
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── src/              # React Native app
│   ├── screens/      # App screens (Login, Home, etc.)
│   ├── components/   # Reusable components
│   ├── services/     # API calls
│   └── context/      # State management
│
├── assets/           # Images and resources
├── App.js            # Entry point
└── package.json
```

---

## ⚙️ How It Works

1. User interacts with mobile app (React Native)
2. App sends requests to backend APIs
3. Backend processes data and stores in database
4. Response is sent back to app and displayed

---

## ▶️ Getting Started

### Backend
```bash
cd backend
npm install
npm run dev
```

### Frontend
```bash
npm install
npm start
```

---

## 🎯 Key Learnings

- Building full-stack mobile applications
- API integration between frontend and backend
- Authentication and data handling
- Working with real-world project structure

---

## 👨‍💻 Author

Varun Reddy
