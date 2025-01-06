# Notification Service

## Overview
Notification Service is a backend application designed to manage and deliver notifications across various channels. This service provides APIs for creating, scheduling, and tracking notifications, ensuring reliable communication with users.

## Features
- **Notification Management:** Create and manage notifications.
- **Multi-Channel Support:** Deliver notifications via email, SMS, or push notifications.
- **Scheduling:** Schedule notifications for future delivery.
- **Delivery Tracking:** Monitor the status of sent notifications.
- **Swagger Documentation:** Comprehensive API documentation for developers.

## Getting Started

### Prerequisites
- Java 11+
- Docker (optional for containerized deployment)
- Gradle

### Steps
1. Clone the repository:
   
   git clone https://github.com/IvanMatiko/notification_service.git
   cd notification_service
2.Build the project: 

./gradlew build

3.Run the application: 

./gradlew bootRun

4.Optional (Build and run with Docker): 

docker build -t post-service . docker run -p 8080:8080 post-service


# API Endpoints
POST /notifications: Create a new notification.
GET /notifications/{id}: Retrieve the details of a specific notification.
PUT /notifications/{id}: Update an existing notification.
DELETE /notifications/{id}: Cancel a notification.
GET /notifications: List all notifications with filtering options.
For detailed API specifications, refer to the Swagger documentation.

# Technologies Used
Java: Core programming language.

Spring Boot: Framework for backend development.

Gradle: Build automation tool.

Swagger: API documentation.

Docker: For containerized deployment.
