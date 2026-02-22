# 🎬 Movies – Full Stack Movie Review Application

A modern full-stack movie platform built with **React + Spring Boot**, allowing users to browse movies, watch trailers, and submit reviews.

This project demonstrates scalable backend architecture, REST API design, and dynamic frontend integration.

---

## 🚀 Features

- 🎥 Browse Movies
- ▶ Watch Trailers
- ✍ Submit & View Reviews
- 🔄 RESTful API Integration
- 🌐 CORS Enabled Backend
- 📦 Maven-based Spring Boot backend
- ⚡ Axios-powered frontend communication

---

## 🏗️ Architecture

Frontend (React)
⬇
Axios API Calls
⬇
Spring Boot REST API
⬇
MongoDB Database

---

## 🛠️ Tech Stack

### 🔹 Frontend
- React.js
- Axios
- CSS
- Component-based architecture

### 🔹 Backend
- Spring Boot
- Maven
- MongoDB
- REST Controllers
- Service Layer Pattern
- Repository Layer Pattern

---

## 📂 Project Structure


movies/
│
├── frontend (React)
│ ├── components/
│ ├── api/
│ └── App.js
│
└── backend (Spring Boot)
├── Controller
├── Service
├── Repository
├── Model
└── application.properties


---

## ⚙️ Installation & Setup

### 🔹 Backend (Spring Boot)

1. Navigate to backend folder:

cd movies/movies


2. Run using Maven:

./mvnw spring-boot:run


Backend runs on:

http://localhost:8080


---

### 🔹 Frontend (React)

1. Navigate to frontend:

cd src


2. Install dependencies:

npm install


3. Start frontend:

npm start


Frontend runs on:

http://localhost:3000


---

## 📡 API Endpoints

### 🎬 Movies
- `GET /api/v1/movies`

### ✍ Reviews
- `POST /api/v1/reviews`
- `GET /api/v1/reviews/{movieId}`

---

## 🧠 Design Principles Used

- Clean Architecture (Controller → Service → Repository)
- Separation of Concerns
- RESTful API Design
- Component Reusability
- CORS Configuration for Frontend Integration

---

## 🔮 Future Improvements

- 🔐 User Authentication
- ❤️ Like & Rating System
- 🔍 Search & Filter
- 📱 Responsive Enhancements
- 🚀 Deployment on Render / Railway / Vercel

---

## 🧭 Author

**Aashutosh Pandey**

Architecting Intelligent Systems • Backend Engineering • Problem Solving

GitHub: https://github.com/itsAashutosh

---

## ⭐ If you like this project

Give it a star ⭐ and feel free to fork and contribute!
