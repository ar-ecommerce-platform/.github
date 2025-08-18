# E-Commerce Microservices Platform Infrastructure

Welcome to the foundational infrastructure repository for a production-grade, microservices-based e-commerce backend built with **Java Spring Boot**. This project is a personal initiative to gain hands-on experience designing scalable distributed systems, applying real-world DevOps practices, and building enterprise-grade CI/CD pipelines.

This GitHub organization hosts the **core infrastructure**, **shared tooling**, and **operational backbone** enabling secure, maintainable development and deployment for a modern e-commerce backend.

---

## 📌 Why This Project?

I created this platform to simulate the kind of architecture and workflows used by real-world engineering teams. The goals include:

- Practicing microservice design patterns using Spring Boot
- Implementing CI/CD pipelines using GitHub Actions
- Managing secrets, configs, and observability like a production system
- Applying infrastructure-as-code with Docker, Helm, and Terraform
- Gaining experience with system design, integration testing, and monitoring

---

## 🧭 Architecture Overview

This platform follows best practices in **microservices architecture**, **DevOps automation**, and **observability** to support a reliable and modular e-commerce system.

### Core Capabilities

- **Authentication & Authorization:** JWT-based auth with RBAC
- **User Management:** Profile and account details
- **Product & Inventory:** Catalog and stock tracking
- **Order & Payment:** Checkout and payment orchestration
- **Notifications:** Email and SMS event triggers
- **API Gateway:** Unified entry point with throttling and auth checks
- **Service Discovery:** Dynamic registry with Eureka
- **Centralized Config:** Externalized config via Spring Cloud Config
- **Secrets Management:** Vault-integrated secrets and templated `.env`s
- **Observability:** ELK stack with structured logging
- **CI/CD:** Reusable GitHub Actions for linting, testing, security, and Docker publishing

---

## 🧰 Tooling & Infrastructure

- **Local Dev:** Docker Compose environment with PostgreSQL, Redis, RabbitMQ, and all services
- **CI/CD:** GitHub Actions with reusable workflow templates
- **Testing:** Unit, integration (Testcontainers), coverage, and OWASP scanning
- **Monitoring & Logging:** ELK Stack, future Datadog/Prometheus support
- **Infra-as-Code:** Docker, Helm, and Terraform for infrastructure provisioning

---

## 🛒 E-commerce Platform Repositories

This organization hosts all repositories for the E-commerce Backend platform, including services, infrastructure, tests, and documentation.

### 📦 Core Services  

| Repository | Description |
| --- | --- |
| [auth-service](https://github.com/ar-ecommerce-platform/auth-service) | User authentication and JWT management |
| [user-service](https://github.com/ar-ecommerce-platform/user-service) | Manages user profiles and account details |
| [product-service](https://github.com/ar-ecommerce-platform/product-service) | Manages product catalog and metadata |
| [inventory-service](https://github.com/ar-ecommerce-platform/inventory-service) | Tracks stock levels and inventory |
| [order-service](https://github.com/ar-ecommerce-platform/order-service) | Handles order placement and tracking |
| [payment-service](https://github.com/ar-ecommerce-platform/payment-service) | Processes and verifies payments |
| [notification-service](https://github.com/ar-ecommerce-platform/notification-service) | Sends emails and system alerts |


### ⚙️ Configuration & Infrastructure  

| Repository | Description |
| --- | --- |
| [config-server](https://github.com/ar-ecommerce-platform/config-server) | Centralized configuration service |
| [config-repo](https://github.com/ar-ecommerce-platform/config-repo) | Centralized configs for all services |
| [api-gateway](https://github.com/ar-ecommerce-platform/api-gateway) | Routes and secures external API traffic |
| [discovery-server](https://github.com/ar-ecommerce-platform/discovery-server) | Eureka-based service registry for dynamic service discovery |
| [infra](https://github.com/ar-ecommerce-platform/infra) | Infrastructure as code: Docker, Kubernetes, secrets |
| [monitoring](https://github.com/ar-ecommerce-platform/monitoring) | Dashboards, alerts, and metrics setup |
| [ci-workflows](https://github.com/ar-ecommerce-platform/ci-workflows) | Shared CI/CD workflows for services |


### 🧪 Testing & Quality  

| Repository | Description |
| --- | --- |
| [e2e-tests](https://github.com/ar-ecommerce-platform/e2e-tests) | End-to-end API and flow tests |
| [test-reports](https://github.com/ar-ecommerce-platform/test-reports) | Stores and displays test results |


### 📖 Documentation  

| Repository | Description |
| --- | --- |
| [docs](https://github.com/ar-ecommerce-platform/docs) | Architecture diagrams, ADRs, and system design docs |

---

## 🚧 Status

This platform is under active development and evolving toward a realistic, production-ready architecture. Contributions, feedback, or suggestions are welcome as I continue to expand, learn, and refine the system.

