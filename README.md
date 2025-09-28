# Advanced Online Bookstore Microservices System

This project implements an advanced online bookstore using Spring Boot microservices. It focuses on asynchronous communication, resilient design, and centralized configuration.

## Services
- **Book Service**: CRUD for book details (PostgreSQL)
- **User Service**: User account management (MongoDB)
- **Order Service**: Order placement/processing (MySQL, Resilience4j circuit breaker)
- **Notification Service**: Email notifications for order confirmations (Kafka)

## Key Components
- **API Gateway**: Routes all external requests
- **Message Broker**: Apache Kafka for event-driven communication
- **Circuit Breaker**: Resilience4j in Order Service
- **Centralized Configuration**: Spring Cloud Config Server
- **Monitoring**: Micrometer, Prometheus, Grafana

## Getting Started
1. Clone the repository
2. Start databases (PostgreSQL, MongoDB, MySQL)
3. Start Kafka and Config Server
4. Build and run each microservice
5. Access API Gateway for external requests

## Monitoring
- Metrics are collected via Micrometer and Prometheus
- Visualize metrics in Grafana

## Folder Structure
- `/book-service`  
- `/user-service`  
- `/order-service`  
- `/notification-service`  
- `/api-gateway`  
- `/config-server`  
- `/monitoring`  

---

Replace placeholder configs and credentials with your own for production use.
