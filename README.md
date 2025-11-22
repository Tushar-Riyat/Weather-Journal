# 📔 Smart Journal Platform

A robust, secure, and scalable journaling application built with the **Spring Boot** ecosystem. This platform goes beyond standard CRUD operations by integrating distributed system patterns, real-time data enrichment, and asynchronous processing.

## 🚀 Key Features

*   **Secure Authentication**: Robust security using **Spring Security** with **JWT** (JSON Web Tokens) and **Google OAuth2** integration.
*   **Event-Driven Architecture**: Decoupled architecture using **Apache Kafka** for asynchronous processing (e.g., weekly sentiment analysis reporting).
*   **High Performance**: Implements **Redis** caching to optimize API response times and reduce database load.
*   **Data Persistence**: Utilizes **MongoDB** for flexible, schema-less data storage, supporting complex nested documents for journal entries.
*   **External Integrations**:
    *   **Weather API**: Automatically enriches journal entries with real-time weather data based on location.
    *   **Email Service**: Automated notifications and reports using JavaMailSender.
*   **Robust Testing**: Comprehensive unit and integration testing support.

## 🛠️ Tech Stack

*   **Backend Framework**: Spring Boot 2.7+
*   **Language**: Java 17+
*   **Database**: MongoDB (NoSQL)
*   **Caching**: Redis
*   **Messaging**: Apache Kafka
*   **Security**: Spring Security, JWT, OAuth2
*   **Build Tool**: Maven
*   **Documentation**: SpringDoc OpenAPI (Swagger UI)

## 🏗️ Architecture Highlights

*   **Controller-Service-Repository** pattern for clean separation of concerns.
*   **DTOs (Data Transfer Objects)** for secure and efficient data exchange.
*   **Global Exception Handling** for consistent API error responses.
*   **Transactional Management** for data integrity across MongoDB operations.

## 🚦 Getting Started

### Prerequisites
*   Java Development Kit (JDK) 1.8 or higher
*   Maven
*   MongoDB (Local or Atlas)
*   Redis
*   Kafka (Zookeeper + Broker)

### Installation
1.  Clone the repository:
    ```bash
    git clone https://github.com/Tushar-Riyat/journalApp.git
    ```
2.  Configure `application.properties` (or `application.yml`) with your database and API credentials.
3.  Build the project:
    ```bash
    mvn clean install
    ```
4.  Run the application:
    ```bash
    mvn spring-boot:run
    ```

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
