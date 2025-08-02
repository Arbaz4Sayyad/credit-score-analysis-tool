# Credit Score Analysis Tool

A prototype of a **Credit Score Analysis System** built with **Java**, **Spring Boot**, and **MySQL**. This project simulates how financial institutions might assess creditworthiness based on customer data and financial behavior.

> ✅ This is a standalone, non-commercial demo project — created for educational purposes and to showcase backend development skills.

---
## 🧩 Overview
The **Credit Score Analysis Tool** automates the evaluation of customer credit scores using real-time data from financial records and external credit bureaus. Built with a microservices architecture using Spring Boot and deployed via Docker and Kubernetes.

## 🎯 Features
- Real-time credit score calculation via Kafka
- REST APIs for each service (User, Credit, Report, Data Collection)
- OAuth2 secure authentication
- Redis caching for optimized performance
- Microservice logging and monitoring via Splunk and Log4j2

## ⚙️ Architecture
- **Frontend**: Angular 10
- **Backend**: Spring Boot (Java)
- **API Gateway**: Spring Cloud Gateway
- **Database**: MySQL (multi-service schema)
- **Messaging**: Apache Kafka
- **Cache**: Redis
- **CI/CD**: Jenkins + GitLab
- **Containerization**: Docker + Kubernetes
- **Monitoring**: Splunk, Log4j2

## 📂 Microservices
1. **User Management Service**
2. **Credit Scoring Service**
3. **Data Collection Service**
4. **Report Service**

## 📌 Tech Stack
| Component | Technology |
|----------|-------------|
| Backend | Spring Boot, Java |
| Frontend | Angular 10 |
| Database | MySQL |
| Messaging | Apache Kafka |
| Cache | Redis |
| Logging | Log4j2, Splunk |
| CI/CD | Jenkins, GitLab |
| Deployment | Docker, Kubernetes |

## 📬 API Documentation
- ✅ [Postman Collection](#)
- ✅ [Swagger/OpenAPI Spec](#)
- 📘 See `/docs` folder for usage samples

## 🔒 Security
OAuth2 integration for secure authentication and role-based access.

## 🧪 Testing
Unit and integration tests using JUnit and Mockito (samples in `/test` folder)

## 🚀 How to Run
```bash
# Pre-requisites: Docker, MySQL, Redis, Kafka

# Step 1: Clone the repo
git clone https://github.com/yourusername/credit-score-analysis-tool.git

# Step 2: Run Docker containers
docker-compose up --build

# Step 3: Access APIs via Postman or Swagger


## 📌 Architecture Overview

![Credit Score Analysis Architecture](./f93833e7-bfbd-494c-b688-81b5f701f1a6.png)


📌 Why This Project?
This project was built to:

Showcase enterprise-grade Java backend development

Practice API design, database interactions, and modular architecture

Demonstrate clean code, error handling, and service layers

## 🙋‍♂️ Author
**Arbaz Sayyad** 
Full Stack Java Developer | Open to New Opportunities
📧 arbaz4sayyad@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/arbaz-sayyad/)
🌐 [Portfolio](https://arbaz4sayyad.github.io/MyPortfolio/)


## 📄 License

This project is for demonstration purposes and not intended for production use.
