# 🎉 EventMate AI
### *An Intelligent Event Planning and Scheduling Platform*

[![React](https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Spring Boot](https://img.shields.io/badge/Backend-SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Java](https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![MySQL](https://img.shields.io/badge/Database-MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![AI Assistant](https://img.shields.io/badge/Feature-AI%20Assistant-purple?style=for-the-badge)]()

**EventMate AI** is a modern **AI-powered event planning and scheduling platform** that simplifies event discovery, booking, and management. The system provides **three role-based dashboards (User, Organizer, and Admin)** with secure authentication and intelligent event interaction.

Built using **React, Spring Boot, and MySQL**, the platform demonstrates a scalable full-stack architecture with role-based system management and smart assistant features.

---

# 📖 Overview

EventMate AI is designed to streamline how events are **created, managed, and attended**.

The platform provides:

- Secure **Login and Registration**
- **Role-Based Dashboards**
- **Event Management System**
- **Event Booking and Monitoring**
- **AI Assistant for user support**
- **Feedback and Review System**

The system connects **users, organizers, and administrators** within a unified event ecosystem.

---

# 🎯 Mission

To create an **intelligent event ecosystem** that simplifies event planning through **AI assistance, automated reminders, and role-based management** while providing a seamless user experience.

---

# 🏗️ System Architecture

The platform follows a **3-Tier Architecture**:

1. **Frontend Layer – React**
2. **Backend Layer – Spring Boot**
3. **Database Layer – MySQL**

```
React Frontend
      │
      │ REST API
      ▼
Spring Boot Backend
      │
      ▼
MySQL Database
```

---

# ✨ Key Features

### 🔐 Secure Authentication
- User Registration
- Login System
- Role-based Access Control

### 📅 Event Management
Organizers can:
- Create Events
- Update Events
- Manage Event Details
- Monitor Event Bookings

### 🎟️ Event Booking
Users can:
- Browse available events
- Book events
- Track booking history

### 🤖 AI Assistant
The platform includes an **AI Assistant** that helps users:
- Discover events
- Navigate the platform
- Get quick assistance

### ⭐ Feedback & Reviews
Users can provide feedback after attending events.

### 🔔 Event Reminder System
Organizers can send reminders to users before the event begins.

---

## 👥 User Roles & Capabilities

### 👤 User Dashboard
- Browse and explore available events
- Book events easily
- View and manage **My Bookings**
- Provide **feedback and reviews**
- Interact with **AI Assistant** for event recommendations and support

---

### 🧑‍💼 Organizer Dashboard
- Create and publish new events
- Update or manage existing events
- Monitor event bookings and participant details
- Manage and respond to user reviews
- Send **event reminders and notifications** to attendees

---

# 📊 Admin Dashboard

The **Admin Dashboard** provides real-time system monitoring including:

- Total Users
- Total Organizers
- Total Events
- Total Bookings

Admins can track platform activity and manage system resources efficiently.

---
# 🛠️ Technology Stack

| Layer | Technology | Description |
|------|------|------|
| Frontend | React | Component-based user interface |
| Backend | Spring Boot | REST API and business logic |
| Programming Language | Java | Core backend development |
| Database | MySQL | Relational data storage |
| API Communication | REST APIs | Frontend–Backend interaction |
| Build Tool | Maven | Dependency management |

---

# 📂 Project Structure

```
EVENTMATE_AI
│
├── backend
│   ├── controller
│   ├── service
│   ├── repository
│   ├── model
│   └── EventMateApplication.java
│
├── frontend
│   ├── components
│   ├── pages
│   ├── services
│   └── App.js
│
├── database
│   └── eventmate.sql
│
├── README.md
└── .gitignore
```

---

## ⚙️ Prerequisites

Before running this project, ensure the following software is installed on your system.

| Software | Recommended Version |
|----------|---------------------|
| Java JDK | 17+ |
| Spring Boot | 3.x |
| Node.js | 18+ |
| npm / yarn | Latest |
| MySQL | 8.x |
| Apache Maven | 3.8+ |
| Git | Latest |

---

# 🚀 Installation & Setup



---

## Backend Setup (Spring Boot)

```bash
cd backend
mvn spring-boot:run
```

Backend runs on:

```
http://localhost:8080
```

---

## Frontend Setup (React)

```bash
cd frontend
npm install
npm start
```

Frontend runs on:

```
http://localhost:3000
```

---

## Database Setup

Create the database:

```sql
CREATE DATABASE eventmate;
```

Update credentials in:

```
application.properties
```

Example configuration:

```
spring.datasource.url=jdbc:mysql://localhost:3306/eventmate
spring.datasource.username=root
spring.datasource.password=yourpassword
```

---


---

