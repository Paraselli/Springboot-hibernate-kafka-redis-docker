# 🚀 Spring Boot + Hibernate + Kafka + Redis + Docker

A scalable **backend microservices application** built using **Spring Boot, Hibernate (JPA), Apache Kafka, Redis, and Docker**.
This project demonstrates **event-driven architecture**, **data persistence**, and **high-performance system design**.

---

## 🧩 Tech Stack

* **Backend**: Spring Boot, Spring MVC
* **Persistence**: Hibernate / JPA
* **Messaging**: Apache Kafka
* **Caching**: Redis
* **Database**: MySQL / PostgreSQL (configurable)
* **Containerization**: Docker, Docker Compose
* **Build Tool**: Maven

---

## ⚙️ Features

* ✅ RESTful APIs for user management
* ✅ Kafka Producer for event publishing
* ✅ Redis caching for performance optimization
* ✅ Hibernate ORM for database operations
* ✅ Dockerized application setup
* ✅ Layered architecture (Controller → Service → Repository)

---

## 🏗️ Architecture

* **Controller Layer** → Handles API requests
* **Service Layer** → Business logic
* **Repository Layer** → Database access using JPA
* **Kafka Producer** → Sends events asynchronously
* **Redis Cache** → Improves response time

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash id="j1x2aa"
git clone https://github.com/Paraselli/Springboot-hibernate-kafka-redis-docker.git
cd Springboot-hibernate-kafka-redis-docker
```

---

### 2️⃣ Start services using Docker

```bash id="l7v4pq"
docker-compose up -d
```

---

### 3️⃣ Run the application

```bash id="0x4f9t"
mvn clean install
mvn spring-boot:run
```

---

## 📡 API Example

### Create User

```http id="9l8n9o"
POST /users
```

```json id="8y7m3d"
{
  "name": "Ram",
  "email": "ram@example.com"
}
```

---

## 🔥 Use Cases

* Event-driven backend systems
* High-performance APIs with caching
* Scalable microservices architecture
* Asynchronous processing using Kafka

---

## 📌 Future Enhancements

* Add Kafka Consumer for event processing
* Implement Circuit Breaker (Resilience4j)
* Add API Gateway (Spring Cloud)
* Deploy to Kubernetes

---

## 👨‍💻 Author

**Ram Paraselli**
🔗 linkedin.com/in/ram-paraselli
🔗 github.com/Paraselli

---

## ⭐ Star this repo if you find it useful!
