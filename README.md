# 🚀 Spring Boot Kafka Redis Docker Platform

![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/SpringBoot-3.x-brightgreen)
![Kafka](https://img.shields.io/badge/Kafka-EventDriven-black)
![Redis](https://img.shields.io/badge/Redis-Caching-red)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue)

---

## ⚡ What is this?

A **containerized backend system** demonstrating:

- REST APIs using Spring Boot
- Database operations using Hibernate (JPA)
- Event-driven communication using Kafka
- High-performance caching using Redis
- Fully dockerized environment for easy setup

---

## 🧠 Why this project matters

This is NOT just a basic CRUD app.

It demonstrates:

- Event-driven architecture using Kafka
- Performance optimization using Redis caching
- Clean backend layering (Controller → Service → Repository)
- Containerized deployment using Docker
- Real-world backend integration patterns

---

## 🌐 Live Links

- 🔗 GitHub Repo: https://github.com/Paraselli/springboot-hibernate-kafka-redis-docker
- 📄 API Docs: http://localhost:8080/swagger-ui.html (if enabled)

---

## 🏗️ Architecture Overview

Client (Postman / UI)  
↓  
Spring Boot REST API  
↓  
Service Layer (Business Logic)  
↓  
Kafka Producer → Event Streaming → Kafka Consumer  
↓  
Redis (Caching with TTL)  
↓  
MySQL (Persistent Storage)  
↓  
Docker (Containerized Environment)

---

## 🔄 End-to-End Flow

1. Client sends API request
2. Controller processes request
3. Service layer handles business logic
4. Data stored in MySQL via Hibernate
5. Event published to Kafka
6. Consumer listens and processes event
7. Frequently accessed data cached in Redis

---

## 🔥 Key Features

- 🔐 REST API with clean architecture
- ⚡ Kafka-based async communication
- 🧠 Redis caching with TTL strategy
- 🗄️ MySQL with Hibernate (JPA)
- 🐳 Dockerized multi-service setup
- 📦 Scalable backend design

---

## 🛠 Tech Stack

| Layer     | Technologies           |
|----------|----------------------|
| Backend   | Java 17, Spring Boot |
| ORM       | Hibernate (JPA)      |
| Messaging | Kafka                |
| Cache     | Redis                |
| Database  | MySQL                |
| DevOps    | Docker               |

---

## 📁 Project Structure
