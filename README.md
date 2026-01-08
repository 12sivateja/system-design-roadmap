# 🧭 System Design Roadmap (MEAN Stack Developer)

**Target Audience:** MEAN Stack Developers (MongoDB, Express, Angular, Node.js)  
**Goal:** Crack system design interviews & build scalable production systems

---

## Phase 0: Prerequisites (Foundation)

- JavaScript (ES6+)
- Asynchronous programming (Promises, async/await)
- REST APIs
- Basic Git & Linux
- Basic networking concepts

---

## Phase 1: Web & Backend Fundamentals

### 1. HTTP & Web Architecture
- HTTP methods (GET, POST, PUT, PATCH, DELETE)
- Status codes (2xx, 4xx, 5xx)
- Headers, cookies, sessions
- REST vs GraphQL vs RPC

### 2. API Design Best Practices
- RESTful resource naming
- API versioning (`/api/v1`)
- Pagination, filtering, sorting
- Idempotent APIs
- Rate limiting

---

## Phase 2: Database & Data Modeling

### 3. MongoDB (Deep Dive)
- Schema design
- Embedding vs referencing
- Indexing (single, compound, TTL, text)
- Aggregation pipeline
- Transactions

### 4. Scalability in MongoDB
- Replication
- Sharding (basics)
- Read/write concerns

### 5. SQL vs NoSQL (Conceptual)
- ACID vs BASE
- CAP theorem
- When NOT to use MongoDB

---

## Phase 3: Scalability Fundamentals

### 6. Scaling Strategies
- Vertical vs horizontal scaling
- Stateless vs stateful services
- Load balancers (L4 vs L7)

### 7. Node.js Performance
- Event loop
- Non-blocking I/O
- Cluster mode
- Worker threads

---

## Phase 4: Caching & Performance

### 8. Caching Strategies
- In-memory caching
- Redis fundamentals
- Cache-aside pattern
- Write-through vs write-back
- Cache invalidation strategies

---

## Phase 5: Reliability & Fault Tolerance

### 9. Failure Handling Patterns
- Retry mechanisms
- Exponential Backoff
- Circuit Breaker
- Timeout handling
- Bulkhead pattern

### 10. Graceful Degradation
- Fallback responses
- Partial system availability

---

## Phase 6: Messaging & Asynchronous Systems

### 11. Messaging Systems
- Message queues vs Pub/Sub
- Kafka basics
- RabbitMQ
- AWS SQS

### 12. Event-Driven Architecture
- Producers & consumers
- At-least-once vs exactly-once delivery
- Idempotent consumers

---

## Phase 7: Security & Authentication

### 13. Authentication & Authorization
- JWT-based auth
- Session-based auth
- OAuth 2.0
- Refresh tokens
- RBAC (Role-Based Access Control)

### 14. Web Security
- HTTPS & TLS
- CORS
- CSRF
- XSS
- Rate limiting & throttling

---

## Phase 8: Observability & Operations

### 15. Logging & Monitoring
- Structured logging
- Centralized logging
- Metrics & alerting

**Tools:**
- Winston / Pino
- ELK Stack
- Prometheus & Grafana

---

## Phase 9: Deployment & DevOps

### 16. Deployment Strategies
- Environment configuration
- CI/CD pipelines
- Blue-Green deployment
- Canary releases

### 17. Infrastructure Basics
- Docker
- Kubernetes (basics)
- Nginx
- PM2

---

## Phase 10: Frontend System Design (Angular)

### 18. Angular Architecture
- Module-based design
- Smart vs dumb components
- Lazy loading
- State management (NgRx)

### 19. Frontend Performance
- Change detection
- OnPush strategy
- Code splitting
- SSR vs CSR

---

## Phase 11: Cloud Architecture

### 20. Cloud Fundamentals
- Monolith vs Microservices
- API Gateway
- Service discovery
- Configuration management

**Cloud Concepts:**
- Compute
- Load balancing
- Object storage
- Managed databases

---

## Phase 12: Interview-Oriented System Design

### 21. Classic Design Problems
- URL Shortener
- Authentication System
- Chat Application
- Notification System
- Online Exam System
- File Upload Service

---

## Phase 13: System Design Thinking Framework

### How to Answer in Interviews
1. Clarify requirements
2. Define APIs
3. High-level architecture
4. Database design
5. Scaling strategy
6. Caching
7. Failure handling
8. Security
9. Trade-offs

---

## 6-Month Preparation Plan

| Month | Focus Area |
|------|-----------|
| 1 | HTTP, APIs, MongoDB |
| 2 | Scaling & caching |
| 3 | Messaging & async systems |
| 4 | Security & auth |
| 5 | Cloud & DevOps |
| 6 | Mock interviews & designs |

---

## Final Notes
- Always explain **trade-offs**
- Relate designs to **real MEAN applications**
- Think in terms of **scale, failure, and security**

---

**End of Roadmap**
