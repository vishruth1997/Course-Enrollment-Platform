# Course-Enrollment-Platform

A microservices-based course enrollment platform where students can register, log in, and enroll in courses. Built with Spring Boot, Spring Cloud (Eureka, Zuul), React, MySQL, and Hibernate for a modular and scalable full-stack application.

---

## 📁 Application Structure

- **microservice-user-management** – Microservice implemented using Spring Boot. 
- **microservice-course-management** – Microservice implemented using Spring Boot.   
- **eureka-discovery-service** – Microservice implemented using Spring Eureka.  
- **zuul-gateway-service** – Microservice implemented using Spring Zuul. 
- **client-side** – A Node.js application implemented using React. This consumes services hosted by the server side. 

---

## 🛠️ Build & Run Instructions

1. **Build Spring Boot Microservices**

```bash
cd <microservice-path>
./gradlew bootJar
./gradlew bootRun
```

2. **Build and Run Client-side Application**

```bash
cd client-side
npm install
npm start
```

---

## 🌐 Access the Application

Visit the app at:  
http://localhost:3000
