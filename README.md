# RideX
A full-stack On-Demand Intercity Ride Booking System that allows users to book rides between cities and drivers to accept requests. Built using Java, Spring Boot, React.js, and SQL with secure JWT authentication.
# 🚗 On-Demand Intercity Ride Booking System

## 📌 Project Summary (Resume‑Ready)

A full‑stack web application that enables users to book intercity rides, connects passengers with drivers, and manages ride lifecycle using secure REST APIs and JWT authentication.

**Tech Stack:** Java, Spring Boot, Spring Security, JWT, React.js, HTML, CSS, JavaScript, MySQL

---

## 🎯 Key Highlights

* Secure authentication using JWT
* Intercity ride search and booking
* Driver acceptance and ride lifecycle management
* Admin dashboard for monitoring users and rides
* Clean layered architecture (Controller → Service → Repository)

---

## 🧑‍💻 User Roles & Capabilities

### Passenger

* Register / Login
* Search intercity rides
* Book rides
* Track ride status
* View booking history

### Driver

* Register / Login
* Accept or reject ride requests
* Update ride status (Started, Completed)

---

## ⚙️ Core Features

* JWT‑based authentication & authorization
* Distance‑based fare calculation
* Real‑time ride status updates
* Booking history management
* Global exception handling

---

## 🗂️ System Modules

1. **Authentication Module**

   * User & driver registration
   * Login with JWT token generation

2. **Ride Booking Module**

   * Ride search between cities
   * Fare estimation
   * Ride confirmation

3. **Driver Module**

   * Ride request handling
   * Ride status updates

---

## 🔌 API Endpoints (Sample)

### Authentication APIs

* `POST /api/auth/register`
* `POST /api/auth/login`

### Ride APIs

* `POST /api/rides/book`
* `GET /api/rides/{rideId}`
* `GET /api/rides/user/{userId}`

### Driver APIs

* `PUT /api/driver/accept/{rideId}`
* `PUT /api/driver/status/{rideId}`

---

## 🔄 Application Workflow

1. User logs in and searches for an intercity ride
2. System calculates fare and shows ride details
3. User confirms booking
4. Driver receives and accepts the request
5. Ride status updates from *Booked → Started → Completed*
6. User can view booking history

---

## 🚧 Challenges & Solutions

### Challenge 1: Secure authentication

**Solution:** Implemented JWT with Spring Security to protect APIs

### Challenge 2: Ride status consistency

**Solution:** Used enums and validation logic to control ride flow

### Challenge 3: Database relationships

**Solution:** Proper mapping between User, Driver, and Ride entities

---

## 📈 Future Enhancements

* Online payment gateway
* Ride cancellation feature
* Ratings & reviews
* Mobile application support

---

## 🎤 Interview Explanation (Quick)

> “This project is an on‑demand intercity ride booking system built using Spring Boot and React. Users can book rides between cities, drivers can accept requests, and admins can monitor the system. I implemented JWT authentication for security and followed a layered architecture to keep the code clean and maintainable.”

---

## 👤 Author

**Komandla Akash**
Java Full Stack Developer

---

⭐ *This project demonstrates real‑world backend architecture, secure authentication, and REST API design.*
