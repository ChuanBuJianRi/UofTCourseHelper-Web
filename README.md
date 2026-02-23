# 🎓 UofT Course Helper

🌐 Live Demo: https://app.uoftcoursehelper.com  

UofT Course Helper is a full-stack academic planning and course exploration platform designed for University of Toronto students. It provides structured course data, intelligent filtering, discussion features, and AI-assisted suggestions to help students navigate course selection more efficiently.

---

## 📌 Overview

This platform was built to simplify academic planning by offering:

- Searchable course database
- Filtering by level and subject
- Course difficulty and rating visualization
- Detailed course information pages
- User authentication system with email verification
- AI-assisted suggestion feature
- Scalable cloud deployment architecture

The system is designed with modular frontend components and RESTful backend services to ensure maintainability and future extensibility.

---

## 🏗️ Tech Stack

**Frontend**
- React
- Dynamic routing
- Component-based UI architecture

**Backend**
- FastAPI
- RESTful API design
- Structured request validation

**Database**
- PostgreSQL (course & user data management)

**Cloud & Deployment**
- AWS S3 (static hosting)
- CloudFront CDN
- Route53 (domain management)

**Security**
- Email verification system
- CAPTCHA human verification
- Password encryption

---

## 🖥️ Application Walkthrough

### 🏠 Home Page

- Global search bar
- Weekly auto-updated campus news
- Navigation: Main / About UofT / Course / Discussion / AI Suggest
- Clean responsive layout

![Home Page](./assets/home.png)

---

### 👤 User Registration

- Secure account creation
- Email verification code
- CAPTCHA human validation
- Password confirmation logic

![Register Page](./assets/register.png)

---

### 🏫 About UofT

- University overview
- Department of Computer Science introduction
- Informational content pages

![About Page](./assets/about.png)

---

### 🔎 Course Explorer

- Search by course code or name
- Filter by course level (100–400)
- Filter by subject category
- Display difficulty and average rating
- Class term indicators

![Course Explorer](./assets/course_explorer.png)

---

### 📄 Course Details

Each course page includes:

- Course description
- Prerequisites
- Exclusions
- Breadth requirements
- Difficulty rating
- Average rating

![Course Details](./assets/course_details.png)

---

## ⚙️ System Architecture

The project follows a decoupled frontend-backend architecture:

- React frontend communicates with FastAPI backend via REST APIs
- Backend handles validation, structured responses, and database interaction
- Static frontend deployed via AWS S3
- CloudFront used for global CDN distribution
- Domain managed with Route53

The architecture is designed to support future extensions such as:

- Personalized course tracking
- User comments and discussion threads
- Real-time AI recommendation engine
- Authentication token system
- Role-based permissions

---

## 🚀 Future Improvements

- Real-time discussion system
- Personalized academic planning dashboard
- ML-based course recommendation
- Performance optimization and caching
- Advanced analytics visualization

---

## 👨‍💻 Author

Developed by Yiyang Gao  
University of Toronto – Computer Science  

---

## 📜 License

This project is for academic and portfolio demonstration purposes.
