# Docker Web Application

A Java Maven web application containerized using Docker with support for Docker Compose and Kubernetes deployment.

## 🚀 Features

- Java Maven Web Application
- Dockerized Application
- Multi-stage Docker Build
- Docker Compose Support
- Kubernetes Deployment
- MySQL Database Integration
- Database Backup Included

## 📁 Project Structure

```
dockerwebapp-master/
│── Docker-app/
│── Docker-db/
│── manifests/
│── compose.yml
│── pom.xml
└── src/
```

## 🛠️ Technologies Used

- Java
- Maven
- Docker
- Docker Compose
- Kubernetes
- MySQL
- Tomcat

## ⚙️ Prerequisites

- Java 8+
- Maven
- Docker
- Docker Compose
- Kubernetes (Optional)

## ▶️ Build the Application

```bash
mvn clean package
```

## 🐳 Build Docker Image

```bash
docker build -t docker-webapp .
```

## 🚀 Run Using Docker

```bash
docker run -d -p 8080:8080 docker-webapp
```

Access the application:

```
http://localhost:8080
```

## 🐳 Run Using Docker Compose

```bash
docker compose up -d
```

## ☸️ Deploy to Kubernetes

```bash
kubectl apply -f manifests/
```

## 📦 Useful Commands

Build

```bash
docker build -t docker-webapp .
```

Run

```bash
docker compose up -d
```

Stop

```bash
docker compose down
```

Kubernetes

```bash
kubectl get pods
kubectl get services
```

## 👨‍💻 Author

**Sravan Reddy**

Senior DevOps Engineer
