# EventEase 🎟️
A scalable, modular event booking and reservation system built using Java Spring Boot and Maven. EventEase allows users to view, book, and manage events with clean architecture, reusable services, and deployment-ready configurations.

---

## 🚀 Features

- 🔧 Built with **Spring Boot** and **multi-module Maven architecture**
- 📦 Modular structure with **separate apps and shared libraries**
- 🧱 Reusable core logic using a shared module (`irctc_common`)
- 🐳 **Dockerized** for seamless containerized deployment
- 🧪 Environment-independent builds with **Maven Wrapper**
- 🧩 Clean separation for future scalability and microservices adoption
- 📂 Preconfigured deployment folder for CI/CD readiness

---

## 🛠️ Tech Stack

- **Java 17**
- **Spring Boot**
- **Maven**
- **Docker**
- **RESTful APIs**
- *(Database integration optional — can plug in MySQL/PostgreSQL easily)*

---

## 📁 Project Structure
eventease/
│
├── apps/                   # Main services
│   ├── admin-service/
│   ├── api-gateway/
│   ├── auth-service/
│   ├── booking-service/
│   └── event-service/
│
├── libs/                   
│   └── irctc_common/       # Shared logic and utilities
│
├── deployment/             # Docker + deployment configs
├── .mvn/                   # Maven wrapper folder
├── mvnw / mvnw.cmd         # Maven wrapper scripts
├── pom.xml                 # Parent build file
