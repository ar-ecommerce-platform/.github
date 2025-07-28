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

## 📂 Repositories in This Platform

| Repository | Purpose |
|-----------|---------|
| `ecommerce-auth-service` | Authentication and RBAC |
| `ecommerce-user-service` | User profile management |
| `ecommerce-product-service` | Product catalog management |
| `ecommerce-inventory-service` | Inventory tracking |
| `ecommerce-order-service` | Order processing |
| `ecommerce-payment-service` | Payment orchestration |
| `ecommerce-notification-service` | Email/SMS notifications |
| `ecommerce-api-gateway` | Gateway service with routing/auth |
| `ecommerce-discovery-server` | Eureka registry |
| `ecommerce-config-server` | Spring Cloud Config server |
| `ecommerce-config-repo` | Externalized config files |
| `ecommerce-test-repo` | Test reports and dashboards |
| `ecommerce-infra-repo` | Infra-as-code, Docker, ELK, Helm |
| `ecommerce-ci-workflows` | Shared CI/CD templates |

---

## 🚧 Status

This platform is under active development and evolving toward a realistic, production-ready architecture. Contributions, feedback, or suggestions are welcome as I continue to expand, learn, and refine the system.

