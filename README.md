<div align="center">

# Arup Mahato

### Java Backend Engineer

Building production backend systems with Java, Spring Boot, REST APIs and microservices,<br>
with a focus on security, payments, data consistency and database performance.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arup-mahato/)
[![Portfolio](https://img.shields.io/badge/Portfolio-24292F?style=flat-square&logo=githubpages&logoColor=white)](https://arupmahato03.github.io/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:arup71062@gmail.com)
[![TradeDrift](https://img.shields.io/badge/TradeDrift-0F766E?style=flat-square&logo=googlechrome&logoColor=white)](https://tradedrift.in)

</div>

---

I'm a Java Backend Engineer with 3+ years of experience building and maintaining Spring Boot services in production. I'm currently at **Togethring Media Labs** and was previously at **Heliverse Technologies**.

Most of my work is on the server side of products: designing and securing REST APIs, integrating payments safely, and keeping the database layer fast and consistent under concurrent load.

---

## What I Work On

| Area | In practice |
|:--|:--|
| **API design** | 10+ Spring Boot microservices and 100+ REST endpoints in production |
| **Security** | Spring Security with JWT authentication and role-based authorization |
| **Payments** | Gateway integrations using idempotency keys and webhook reconciliation to prevent duplicate charges |
| **Database performance** | Resolving Hibernate/JPA N+1 queries, composite indexes, MySQL schema tuning |
| **Caching** | Redis for frequently accessed data |
| **Concurrency** | Transactions and locking strategies to keep a real-time bidding system consistent under simultaneous bids |
| **Integrations** | Third-party REST APIs, webhooks, CRM data sync, Wix plugin services |
| **Analytics** | Event aggregation and reporting APIs for internal dashboards |

---

## Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

| Area | Stack |
|:--|:--|
| **Languages** | Java (8 / 11 / 17), SQL |
| **Core Java** | OOP, Collections, Generics, Multithreading, Streams, Exception Handling |
| **Backend** | Spring Boot, Spring MVC, Spring Data JPA, Spring Security, Spring AOP, Hibernate |
| **Architecture** | Microservices, REST API design, Layered architecture, SOLID |
| **Data** | PostgreSQL, MySQL, MongoDB, Redis, indexing, schema design, transaction management |
| **Security** | JWT, OAuth 2.0, RBAC |
| **Testing** | JUnit 5, Mockito |
| **Tools** | Git, Maven, Docker, Postman, Swagger / OpenAPI, IntelliJ IDEA, Linux |

---

## Experience

### Backend Development Engineer · Togethring Media Labs
`Dec 2024 – Present` · Pune, India

- Designed and delivered **10+ Spring Boot microservices** in production, each independently deployable with its own REST contract.
- Built and secured **100+ REST endpoints** using Spring Security, JWT authentication and role-based authorization.
- Integrated **payment gateway flows** (100+ transactions / month) using idempotency keys and webhook reconciliation to prevent duplicate charges and payment mismatches.
- Improved the data layer by resolving **N+1 queries** in Hibernate/JPA, adding **composite indexes** in MySQL, and introducing **Redis caching** for frequently read data.

<details>
<summary>More</summary>
<br>

- Developed backend services for an analytics platform, aggregating event data and exposing reporting APIs for internal dashboards.
- Built Wix plugin services and CRM integration layers for third-party data synchronization.

</details>

### Java Backend Developer · Heliverse Technologies
`Jun 2023 – Sep 2024` · Gurugram, India

- Engineered a **real-time property bidding system**, using database transactions and locking strategies to maintain data consistency under simultaneous bids.
- Developed Spring Boot REST APIs for a **Customer Management System** serving 500+ active users.
- Implemented payment gateway integration and **role-based access control** across core modules.

---

## TradeDrift

**Trading journal & backtesting platform** · *Backend Engineer | Personal Project*

Traders bring in their trade history from CSV files or broker sync. TradeDrift reconciles it into a clean, normalized ledger and computes performance analytics they can rely on.

```mermaid
flowchart LR
    A["CSV imports /<br/>Broker sync"] --> B["Ingestion &<br/>Reconciliation"]
    B --> C["Normalized trades<br/>(fees + funding)"]
    C --> D["Deterministic<br/>Analytics Engine"]
    D --> E["REST APIs"]
    E --> F["Dashboard"]
    E --> G["AI analysis"]
```

| Problem | Approach |
|:--|:--|
| **Messy source data** | Ingestion and reconciliation pipelines for CSV imports and broker sync; raw fills rebuilt into normalized trades including fees and funding costs |
| **Numbers users can trust** | Deterministic analytics engine: the same trades always produce the same win rate, expectancy, profit factor and drawdown |
| **Tenant isolation** | Multi-tenant data isolation, with every read and write scoped to its tenant |
| **Authentication** | JWT-based authentication |
| **Billing** | Subscription billing across multiple pricing tiers |
| **AI-ready data** | Analytics stored in a structured form for downstream AI analysis |

**Stack:** Java · Spring Boot · PostgreSQL · REST APIs · JWT

[![Live Product](https://img.shields.io/badge/Live_Product-tradedrift.in-0F766E?style=flat-square)](https://tradedrift.in)
[![Portfolio](https://img.shields.io/badge/Portfolio-arupmahato03.github.io-24292F?style=flat-square)](https://arupmahato03.github.io/)

<!--
=========================================================
FEATURED REPOSITORIES — uncomment once a showcase repo is public.
Replace REPO_NAME and the description with real details only.
=========================================================

---

## Featured Repositories

| Repository | What it demonstrates |
|:--|:--|
| [REPO_NAME](https://github.com/arupmahato03/REPO_NAME) | One line on the backend problem it solves |

-->

---

## Currently Deepening

These are areas I'm actively studying and building with. I don't claim production experience in them yet.

`Apache Kafka` · `Distributed Systems` · `System Design` · `Scalable Backend Architecture` · `Cloud (AWS / Oracle Cloud)` · `CI/CD` · `Docker in production deployments`

---

<div align="center">

**Open to backend engineering conversations.**

[LinkedIn](https://www.linkedin.com/in/arup-mahato/) · [Portfolio](https://arupmahato03.github.io/) · [arup71062@gmail.com](mailto:arup71062@gmail.com) · [TradeDrift](https://tradedrift.in)

</div>
