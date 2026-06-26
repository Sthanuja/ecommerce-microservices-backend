# Distributed Event-Driven E-Commerce Microservices

A high-performance enterprise e-commerce backend platform built using a decoupled microservices architecture pattern. 

## Technical Architecture & Core Features

* **Microservices Framework**: Designed independent, single-responsibility business domains using **Spring Boot** and **Spring Cloud**.
* **Service Discovery & Orchestration**: Configured centralized ecosystem management and dynamic instance discovery utilizing a **Netflix Eureka Server**.
* **Centralized Configuration**: Implemented a core **Config Server** to manage distributed property assets dynamically across runtime stages.
* **Distributed Messaging Stream**: Handled asynchronous event-driven communications and decoupled critical order pipelines via **Apache Kafka** event loops.
* **API Gateway Routing**: Structured unified client access points featuring custom load balancing and secure gateway routing profiles.
* **Telemetry & Tracking**: Integrated structural end-to-end request context logging across multi-service transactions.

## Tech Stack
* **Backend Framework**: Java 17, Spring Boot 3.x, Spring Cloud
* **Message Broker**: Apache Kafka
* **Database & Caching**: MySQL, Hibernate/JPA
* **DevOps Infrastructure**: Docker Desktop, Docker Compose
