# devops_assignment

# 🚀 Spring Boot Microservices with Docker, Kubernetes, and CI/CD Pipeline

This project demonstrates a **microservices architecture** built using **Spring Boot**, containerized with **Docker**, orchestrated with **Kubernetes**, and deployed via a **CI/CD pipeline**. The goal is to create scalable, maintainable, and production-ready microservices.

---

📁 Project Structure

customer-service/ ├── src/ ├── target/ ├── Dockerfile ├── pom.xml ├── application.properties └── k8s/ ├── deployment.yaml └── service.yaml

⚙️ Setup Instructions

🔧 Prerequisites

Docker & Docker Compose

Kubernetes (Minikube or alternative)

kubectl CLI

Maven

Java 23

Git

🛠️ Build and Run the Project 

Step 1: Clone the Repository 

git clone https://github.com/NavinKumargs/Java_Microservices-Python-programming.git 
cd Java_Microservices-Python-programming/TailorGang_Springboot/TailorGang 

Step 2: Build the Project 

mvn clean install 

Step 3: Run Locally  

java -jar target/tailorgang.jar

🐳 Running with Docker

1. Build Docker Image

docker build -t tailorgang .

2. Run Docker Container

docker run -p 8870:8080 tailorgang

![Capture](https://github.com/user-attachments/assets/27ad6ff1-52bb-49dc-b801-a30c903c3de9)

☸️ Kubernetes Deployment

1. Enable Kubernetes on Docker Desktop
   
Make sure Kubernetes is enabled under Docker Desktop > Settings > Kubernetes.

2. Apply Kubernetes Manifests

Apply Kubernetes Configs deployment.yaml yaml and service.yaml yaml

![Capture1](https://github.com/user-attachments/assets/b6cbec7a-72fd-400a-9741-345ce9be99ba)

![Capture3](https://github.com/user-attachments/assets/02897921-6b0e-4dc9-8d28-1170e070328d)

kubectl apply -f deployment.yaml

kubectl apply -f service.yaml

3. Access the Application
   
If using Docker Desktop, get the service URL with:

kubectl get svc

![Screenshot (1)](https://github.com/user-attachments/assets/6d9f516b-27da-4d7b-8a90-e1fcdcd6a44f)

Kubernetes Dashboard

![Capture4](https://github.com/user-attachments/assets/0ed491a6-522f-4fae-afe0-5ed05a55d058)













