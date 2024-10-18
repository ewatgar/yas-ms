# yas-ms
YAS: Yet Another Shop - Microservices

### Configuration and Dependencies
- General for Spring Boot projects
  - Spring Boot 3.3.4
  - Maven
  - Jar
  - Java 17
  - Lombok
  - Spring Boot DevTools


- Eureka Server
  - Eureka Server
  - Spring Actuator
  - Port 8761


- API Gateway
  - Spring Cloud Gateway
  - Eureka Discovery Client
  - Port 8080


- Product Microservice
  - Spring Web
  - Spring Boot Actuator
  - Spring Data JPA
  - PostgreSQL Driver
  - Eureka Discovery Client
  - Port 8081


- Order Microservice
  - Spring Web
  - Spring Boot Actuator
  - Spring Data JPA
  - PostgreSQL Driver
  - Eureka Discovery Client
  - OpenFeign
  - Port 8082


- Inventory Microservice
  - Spring Web
  - Spring Boot Actuator
  - Spring Data JPA
  - PostgreSQL Driver
  - Eureka Discovery Client
  - Port 8083


- Databases
  - Docker Compose
  - PostgreSQL
  - PgAdmin
