
# E-Commerce Microservices Platform Infrastructure

Welcome to the foundational infrastructure repository for the **production-grade microservices-based e-commerce backend** built with **Java Spring Boot**. This organization hosts the core infrastructure, shared tooling, and operational backbone enabling scalable, maintainable, and secure development and deployment of the entire e-commerce system.

---

## Overview

This platform follows best practices in microservices architecture, DevOps automation, and observability to power a modern e-commerce backend.

### Core Microservices

| Service                          | Description                                     |
|---------------------------------|------------------------------------------------|
| `ecommerce-auth-service`         | JWT-based authentication and RBAC               |
| `ecommerce-user-service`         | User profile management and account details     |
| `ecommerce-product-service`      | Product catalog management                        |
| `ecommerce-inventory-service`    | Inventory tracking and stock updates             |
| `ecommerce-order-service`        | Order creation and processing                     |
| `ecommerce-payment-service`      | Payment orchestration and workflows               |
| `ecommerce-notification-service` | Email and SMS notifications                        |
| `ecommerce-api-gateway`          | Gateway layer with authentication and throttling |
| `ecommerce-discovery-server`     | Eureka service registry                           |
| `ecommerce-config-server`        | Spring Cloud Config Server                        |
| `ecommerce-config-repo`          | Centralized config files and secrets              |
| `ecommerce-test-repo`            | Automated test, coverage, and security reports    |

### Infrastructure & Tooling

- **Local Development:** Docker Compose environment with PostgreSQL, Redis, RabbitMQ, and all microservices
- **Configuration:** Externalized config management using Spring Cloud Config and Vault integration
- **Service Discovery:** Dynamic service registry powered by Eureka
- **API Gateway:** Spring Cloud Gateway with JWT validation and rate limiting
- **Secret Management:** .env templating and Vault integration for secrets and credentials
- **CI/CD:** Reusable GitHub Actions workflows for build, test, lint, integration testing (Testcontainers), and Docker image publishing
- **Observability:** Centralized logging with ELK stack (Elasticsearch, Logstash, Kibana), consistent log formatting for traceability

---

## Repository Structure

The organization contains the following key repositories:

- **`ecommerce-auth-service`**: Authentication and RBAC microservice  
- **`ecommerce-user-service`**: User management microservice  
- **`ecommerce-product-service`**: Product catalog microservice  
- **`ecommerce-inventory-service`**: Inventory management microservice  
- **`ecommerce-order-service`**: Order processing microservice  
- **`ecommerce-payment-service`**: Payment handling microservice  
- **`ecommerce-notification-service`**: Notification microservice  
- **`ecommerce-api-gateway`**: API gateway service  
- **`ecommerce-discovery-server`**: Service registry  
- **`ecommerce-config-server`**: Config server  
- **`ecommerce-config-repo`**: Central config repo  
- **`ecommerce-test-repo`**: Test reports and dashboards  
- **`ecommerce-infra-repo`**: Infrastructure as code, Docker, Helm charts, ELK, Terraform  
- **`ecommerce-ci-workflows`**: Shared reusable GitHub Actions workflows  
