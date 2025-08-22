🎓 School & Student Microservices System

📌 Objective

A microservices-based system that demonstrates Spring Cloud patterns with service discovery, centralized configuration, API Gateway, and inter-service communication.The system manages Schools and Students, where each service has its own database. It includes service registration/discovery, load balancing, and distributed tracing.

🏗️ Architecture

The system consists of the following services:

Config Server – Centralized configuration management for all microservices.

Discovery Server (Eureka) – Service registry for dynamic service discovery.

API Gateway – Routes external requests to internal services (students, schools).

School Service – Manages school entities and communicates with Student Service using OpenFeign.

Student Service – Manages student entities and associates them with schools.

PostgreSQL + PgAdmin – Persistent storage for school and student services.

Zipkin – Distributed tracing and monitoring.

🛠️ Tools & Technologies

Java 21, Spring Boot 3, Spring Cloud (Eureka, Config Server, Gateway, OpenFeign)

Spring Data JPA, Hibernate, PostgreSQL, Docker, Docker Compose

Zipkin for distributed tracing

RESTful APIs, OpenAPI/Swagger

IntelliJ IDEA, Git/GitHub




<img width="395" height="428" alt="image" src="https://github.com/user-attachments/assets/053c8a06-b215-4c13-bad4-f6a9cd0c5512" />


<img width="682" height="700" alt="image" src="https://github.com/user-attachments/assets/db7565d8-a118-4db5-a525-78b99656feae" />







👨‍💻 Author

Ahmed Farag 📧 farag0336@gmail.com

💻 Passionate about Java & Spring Boot Development
LinkedIn: https://www.linkedin.com/in/ahmed-farag-93a74324a/
