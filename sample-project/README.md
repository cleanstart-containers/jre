# 🚀 JRE Web Application

## Directory Structure of JRE Sample projects
```bash
cleanstart-containers/
└── jre/
    └── sample-project/
        ├── java-web/
        │   ├── Dockerfile
        │   ├── README.md
        │   └── src/
        │       └── main/
        │       └── SimpleHttpServer.java
        |       └── README.md
        │   └── README.md
        │---README.md
```

A complete jre web application built with Spring Boot that demonstrates user management with SQLite database, web interface with Thymeleaf templates, and REST API endpoints.

## Quick Start

### Prerequisites
- Docker installed
- CleanStart jre image pulled

### Run the Application
```bash
cd java-web

# Build and run with Docker
docker build -t jre-web-app .
docker run -p 8080:8080 jre-web-app
```

### Access the Application
- **Web Interface**: http://localhost:8080
- **REST API**: http://localhost:8080/api/users
- **Localhost** : Use localhost in Incognito Windows to avoid cache problems

## Features
- User management with SQLite database
- Thymeleaf-based web interface
- REST API endpoints for CRUD operations
- Docker containerization
- Health monitoring

## API Endpoints
- `GET /api/users` - List all users
- `POST /api/users` - Create new user
- `GET /` - Web interface for user management

## 📚 Resources
- [CleanStart Website](https://cleanstart.com/)

- [Spring Boot Documentation](https://spring.io/projects/spring-boot)

