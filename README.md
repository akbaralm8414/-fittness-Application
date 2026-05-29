AI-POWERED FITNESS APPLICATION

Description
AI-Powered Fitness Application is a full-stack microservices-based web application designed to help users manage fitness activities, track progress, and receive personalized AI-driven fitness recommendations. The system is built using Spring Boot microservices architecture with secure authentication, service discovery, API gateway routing, asynchronous communication using Kafka, and AI integration using Google Gemini/OpenAI APIs.

The application enables users to register securely, log activities, monitor fitness goals, and receive intelligent workout and health suggestions through Generative AI.

Features

User Authentication & Authorization using Keycloak OAuth2
Secure API Gateway with Spring Cloud Gateway
Microservices Architecture using Spring Boot
Service Discovery with Eureka Server
AI-powered fitness recommendations using Gemini AI/OpenAI
Activity tracking and management
Asynchronous communication using Apache Kafka
RESTful API-based backend services
Centralized configuration using Spring Cloud Config Server
Responsive frontend using React.js
CRUD operations for users and activities
Database integration with PostgreSQL/MySQL and MongoDB
Docker-based deployment and containerization
End-to-end microservices communication

Tech Stack

Backend

Java
Spring Boot
Spring Security
Spring Cloud Gateway
Eureka Server
Spring Data JPA
Hibernate
Apache Kafka
REST APIs
OAuth2 & Keycloak

Frontend

React.js
HTML5
CSS3
JavaScript
Database
PostgreSQL
MySQL
MongoDB

DevOps & Tools

Docker
Maven
Postman
Git & GitHub

AI Integration

Google Gemini AI API
OpenAI API

Application Architecture

The application follows a distributed microservices architecture where different services communicate through REST APIs and Kafka messaging.

Core Services
User Service
Manages user registration and profiles
Handles authentication and authorization

Activity Service
Tracks user fitness activities and workout data
Stores activity logs in MongoDB

AI Recommendation Service
Generates personalized fitness and health recommendations
Uses Generative AI models for intelligent suggestions

API Gateway
Centralized routing and security
Handles authentication using Keycloak

Eureka Server
Service discovery and registration
Config Server
Centralized configuration management


Project Structure
AI-Powered-Fitness-Application
│
├── api-gateway
├── config-server
├── eureka-server
├── user-service
├── activity-service
├── ai-service
├── frontend-react
├── docker
└── README.md

API Endpoints

User Service
Method	Endpoint	Description
POST	/users/register	Register new user
GET	/users	Get all users
GET	/users/{id}	Get user by ID
PUT	/users/{id}	Update user
DELETE	/users/{id}	Delete user


Activity Service
Method	Endpoint	Description
POST	/activities	Add activity
GET	/activities	Get all activities
GET	/activities/{id}	Get activity by ID
PUT	/activities/{id}	Update activity
DELETE	/activities/{id}	Delete activity

AI Recommendation Service
Method	Endpoint	Description
POST	/ai/recommend	Generate fitness recommendations
GET	/ai/history	View recommendation history

Security Features

OAuth2 Authentication
Keycloak Identity Management
JWT-based Authorization
Secure API Gateway Routing
Role-based Access Control
Kafka Workflow

User logs activity
Activity Service publishes event to Kafka
AI Service consumes activity data
AI generates personalized recommendations
Recommendations are sent back to users

How to Run
Prerequisites
Java 17+
Maven
Docker
PostgreSQL/MySQL
MongoDB
Apache Kafka

Steps

Clone Repository
git clone https://github.com/akbaralm/AI-Powered-Fitness-Application.git
Configure Databases
Update database configurations in:

application.properties
Start Required Services
Kafka
MongoDB
PostgreSQL/MySQL
Keycloak
Run Backend Services
mvn spring-boot:run
Run Frontend
npm install
npm start

Future Enhancements
Wearable device integration
Real-time fitness analytics
AI chatbot fitness assistant
Cloud deployment on AWS
Push notifications
Workout video recommendations
Learning Outcomes
Built scalable microservices architecture
Implemented secure authentication using OAuth2 & Keycloak
Worked with Kafka-based asynchronous communication
Integrated Generative AI APIs
Developed RESTful APIs using Spring Boot
Implemented API Gateway and Service Discovery
Built responsive frontend using React.js
Gained experience with Docker and distributed systems

Author
Akbar Alam Aspiring Java Full Stack & Backend Developer

Java | Spring Boot | Microservices | React.js
AI Integration | Kafka | Docker | REST APIs
GitHub:https://github.com/akbaralm8414/
LinkedIn: https://www.linkedin.com/in/akbar-alam2345/
