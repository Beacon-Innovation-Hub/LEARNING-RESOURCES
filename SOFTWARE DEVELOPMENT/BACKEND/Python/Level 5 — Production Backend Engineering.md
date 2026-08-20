# Level 5 — Production Backend Engineering

> Move from a working Django API to a production-style backend that is deployable, observable, maintainable and resilient.

**Stage:** Advanced / Junior Backend Developer Readiness  
**Prerequisite:** Levels 1–4

---

## Learning Outcomes

- [ ] Separate development and production configuration
- [ ] Containerize a backend
- [ ] Explain WSGI vs ASGI
- [ ] Understand reverse proxies
- [ ] Use caching appropriately
- [ ] Understand background tasks
- [ ] Build CI/CD checks
- [ ] Log and monitor application behaviour
- [ ] Optimize common database queries
- [ ] Design for failures
- [ ] Document deployment and recovery
- [ ] Compare Django and FastAPI based on requirements

---

# 1. Production Architecture

Understand:

```text
CLIENT
   ↓
HTTPS
   ↓
REVERSE PROXY
   ↓
APPLICATION SERVER
   ↓
DJANGO
   ↓
POSTGRESQL
```

Possible supporting systems:

```text
Redis
Background Worker
Object Storage
Monitoring
Logging
```

Do not add infrastructure without a reason.

---

# 2. Framework Trade-offs

Read:

**[Python Backend Frameworks — Django vs Flask vs FastAPI](https://roadmap.sh/python/backend-framework)**

Understand why:

```text
Django
→ structured/full-featured applications

Flask
→ lightweight applications/prototypes

FastAPI
→ API-focused, typed, async-friendly services
```

The goal is not to replace Django at this stage. It is to learn to justify framework choices.

---

# 3. FastAPI Exposure

FastAPI should be introduced as a second backend approach after learners understand backend principles.

Study:

- type-driven validation
- Pydantic
- OpenAPI
- automatic docs
- async endpoints
- dependency injection concepts

## Practice

Rebuild one small read-only Django endpoint using FastAPI.

Compare:

```text
Project structure
Validation
Documentation
Async support
Database integration
Developer effort
```

Do not rewrite the entire capstone merely to use another framework.

---

# 4. Docker

Learn:

```text
Image
Container
Dockerfile
Volume
Network
Environment Variable
Docker Compose
```

Containerize:

```text
Django
PostgreSQL
```

Development should be reproducible on another machine.

---

# 5. Deployment & CI/CD Video Resource

[![Django React Docker CI/CD](https://img.youtube.com/vi/XHwVOqc68zM/maxresdefault.jpg)](https://www.youtube.com/watch?v=XHwVOqc68zM)

**[▶ Industry-Level Django Deployment — Docker & CI/CD](https://www.youtube.com/watch?v=XHwVOqc68zM)**

Use this as supplementary deployment exposure. Focus on understanding the deployment workflow rather than copying configuration blindly.

---

# 6. WSGI & ASGI

Understand conceptually:

```text
WSGI
Traditional synchronous Python web interface

ASGI
Supports asynchronous applications and long-lived connections
```

Know why the distinction matters for:

- concurrency
- WebSockets
- async endpoints
- deployment servers

---

# 7. Caching

Caching can reduce repeated expensive work.

Possible cached data:

```text
Frequently requested routes
Public configuration
Expensive reports
Reference data
```

Questions before caching:

```text
What is expensive?
How stale may the value become?
How is the cache invalidated?
What happens if Redis/cache is unavailable?
```

Do not cache simply because Redis exists.

---

# 8. Background Tasks

Examples:

```text
Send email
Generate report
Process uploaded file
Create invoice
Recalculate large dataset
Send notification
```

Understand why a user should not always wait for long-running work inside the HTTP request.

Learn the architecture:

```text
REQUEST
   ↓
CREATE JOB
   ↓
QUEUE
   ↓
WORKER
   ↓
RESULT
```

Become familiar with Celery/Redis concepts.

---

# 9. Database Performance

Study:

- indexes
- query counts
- N+1 queries
- `select_related()`
- `prefetch_related()`
- pagination
- database transactions
- connection management — concept

Measure before optimizing.

---

# 10. Observability

A production backend should answer:

```text
Is the application running?
Are requests failing?
Which endpoint is slow?
Is the database reachable?
Are background jobs failing?
Is data fresh?
```

Use:

- structured logs
- error tracking concepts
- health checks
- metrics concepts
- alerts

---

# 11. CI/CD

A basic pipeline:

```text
PUSH / PULL REQUEST
        ↓
INSTALL
        ↓
LINT
        ↓
TEST
        ↓
SECURITY / QUALITY CHECKS
        ↓
BUILD
        ↓
DEPLOY
```

A failed critical test should block normal deployment.

---

# 12. Failure Engineering Practice

Simulate:

1. PostgreSQL unavailable
2. cache unavailable
3. external API timeout
4. invalid environment configuration
5. migration failure
6. worker unavailable
7. duplicate background task
8. large request
9. malformed payload
10. application restart

For each document:

```text
Detection
User impact
Logs
Recovery
Prevention
```

---

# 13. Logic Lab — Peak Transport Demand

A booking service normally receives:

```text
20 requests/minute
```

During holiday periods:

```text
2 000 requests/minute
```

Reason about:

- database load
- seat availability
- race conditions
- caching
- scaling
- rate limits
- monitoring

Do not begin by saying "use microservices."

Start with the bottleneck.

---

# 14. Logic Lab — Trade Report Generation

A monthly report takes 90 seconds to generate.

Should the HTTP request remain open for 90 seconds?

Design a background-job workflow:

```text
POST /reports/
      ↓
202 Accepted
      ↓
Job ID
      ↓
Worker Processes Report
      ↓
GET /reports/<job-id>/
```

Explain the status transitions.

---

# Final Competence Project — BIH Regional Commerce & Logistics Backend

Build a production-style backend for a platform coordinating regional trade and transport.

## Domains

```text
Users
Organizations
Products
Suppliers
Orders
Shipments
Routes
Vehicles
Bookings
Payments — simulated records only
Reports
Notifications
```

## Required Capabilities

### API

- RESTful endpoints
- validation
- pagination
- filtering
- correct status codes
- API documentation

### Database

- PostgreSQL
- relationships
- constraints
- migrations
- query optimization

### Security

- authentication
- role-based permissions
- object ownership
- protected management operations
- environment secrets

### Reliability

- automated tests
- error handling
- logging
- health endpoint
- failure-aware external integrations

### Production

- Docker
- environment separation
- CI pipeline
- deployment documentation
- optional justified cache
- optional justified background worker

---

# Required Repository Structure

```text
bih-commerce-logistics-backend/
├── config/
├── apps/
│   ├── accounts/
│   ├── trade/
│   ├── logistics/
│   ├── bookings/
│   └── reports/
├── tests/
├── docs/
│   ├── architecture.md
│   ├── api.md
│   ├── security.md
│   └── deployment.md
├── docker/
├── .github/
│   └── workflows/
├── manage.py
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

Never commit the real `.env`.

---

# Technical Defence

The learner should be prepared to:

1. Trace a request from client to database and back.
2. Explain why Django was selected.
3. Compare Django and FastAPI for one service.
4. Explain every major model relationship.
5. Diagnose an intentionally slow endpoint.
6. Fix an authorization flaw.
7. Explain a failed test.
8. Explain Docker's role.
9. Explain what happens if PostgreSQL fails.
10. Explain when caching helps and when it creates risk.
11. Explain why a task belongs in a background worker.
12. Explain WSGI vs ASGI.
13. Explain how secrets reach production safely.
14. Explain how CI reduces deployment risk.
15. Identify what they would simplify for a small deployment.

The assessor should modify requirements during the defence and require the learner to adapt part of the backend.

---

# Final Assessment

| Area | Weight |
|---|---:|
| Backend architecture | 10% |
| Django/DRF competence | 15% |
| PostgreSQL/data modelling | 15% |
| Business logic | 10% |
| Authentication/security | 15% |
| Testing/reliability | 10% |
| Performance/observability | 10% |
| Docker/CI/deployment | 10% |
| Technical defence | 5% |

**BIH Junior Backend Developer competence threshold: 70%**

Critical security, data-integrity or authorization failures require remediation even if the numerical score exceeds the threshold.

---

# Junior Backend Developer Readiness

A successful learner should independently be able to:

```text
Understand Requirements
        ↓
Model Business Domain
        ↓
Design API
        ↓
Design Database
        ↓
Implement
        ↓
Validate
        ↓
Secure
        ↓
Test
        ↓
Debug
        ↓
Optimize
        ↓
Containerize
        ↓
Deploy
        ↓
Monitor
        ↓
Document
        ↓
Defend Decisions
```

> The goal is not to become a developer who only knows Django syntax. The goal is to become a backend developer who can reason about data, requests, business rules, security, failures and production systems.
