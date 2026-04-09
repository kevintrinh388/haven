# Haven

Haven is a **full-stack social matching web application** designed to provide a privacy-focused experience for discovering profiles, forming matches, and chatting in real time.

Built with a **React + TypeScript frontend** and a **Spring Boot backend**, Haven includes secure authentication, profile management, swipe-based discovery, matching logic, and live messaging.

---

## Repositories

- **Frontend:** [haven-frontend](https://github.com/kevintrinh388/haven-frontend)
- **Backend API:** [haven-backend](https://github.com/kevintrinh388/haven-backend)

---

## Features

### Authentication & Security

- User registration and login
- JWT-based authentication
- Protected routes and secure API access

### User Profiles

- Create and edit user profile
- Upload profile photos
- Check profile completion status

### Discovery & Matching

- Swipe-based profile discovery
- Match creation based on user interactions
- Browse discovered users and matches

### Real-Time Messaging

- Live chat between matched users
- Message seen status
- WebSocket/STOMP-based messaging system

---

## Tech Stack

### Frontend

- **React**
- **TypeScript**
- **Vite**
- **CSS**

### Backend

- **Java 17**
- **Spring Boot**
- **Spring Security**
- **REST APIs**
- **WebSockets (STOMP)**

### Database & Auth

- **PostgreSQL**
- **JWT Authentication**

---

## Architecture

Haven uses a **decoupled full-stack architecture**:

```text
React + TypeScript Frontend
            ↓
   Spring Boot REST API
            ↓
       PostgreSQL DB

     + WebSocket/STOMP
   for real-time messaging
```
