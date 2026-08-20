# Python Backend Development

> A structured Beacon Innovation Hub learning pathway for progressing from Python programming foundations to production-ready backend development.

**Track:** Software Development  
**Specialisation:** Backend Development  
**Primary Language:** Python  
**Primary Framework:** Django  
**API Framework:** Django REST Framework  
**Database:** PostgreSQL  
**Learning Model:** Watch → Read → Reason → Practice → Build → Test → Defend

---

## Overview

This folder contains the Python backend development pathway.

The pathway is designed for learners who already understand Python fundamentals and are ready to apply Python to real server-side systems.

The focus is not only on learning framework syntax. Learners are expected to understand how backend systems receive requests, apply business rules, interact with databases, protect data, expose APIs, handle failures, and operate in production environments.

```text
Python Foundations
        ↓
Web & Backend Foundations
        ↓
Django Web Development
        ↓
PostgreSQL & REST APIs
        ↓
Authentication, Security & Testing
        ↓
Production Backend Engineering
        ↓
Competence Project
        ↓
Technical Defence
        ↓
Junior Backend Developer Readiness
```

---

# Prerequisite — Python Foundations

Before starting this pathway, learners should be comfortable with:

- [ ] Variables and data types
- [ ] Operators
- [ ] Conditionals
- [ ] Loops
- [ ] Functions
- [ ] Lists, tuples, sets and dictionaries
- [ ] File handling
- [ ] Exception handling
- [ ] Modules and packages
- [ ] Virtual environments
- [ ] Object-oriented programming
- [ ] Comprehensions
- [ ] Basic data structures and algorithms
- [ ] Type hints
- [ ] Automated testing
- [ ] Git and GitHub fundamentals

A learner who still struggles to solve ordinary Python problems independently should complete the Python Foundations pathway before beginning backend development.

---

# Learning Levels

| Level | Stage | Main Competence |
|---|---|---|
| **Level 1** | Backend Foundations | HTTP, client-server architecture, JSON, APIs and REST |
| **Level 2** | Django Development | Django architecture, models, views, URLs, forms and CRUD |
| **Level 3** | Data & API Engineering | PostgreSQL, Django ORM, DRF and REST API development |
| **Level 4** | Secure Backend Development | Authentication, authorization, security and automated testing |
| **Level 5** | Production Engineering | Docker, performance, caching, background work, CI/CD and deployment |

---

# Level 1 — Web & Python Backend Foundations

**[Open Level 1 →](Python-Backend-Level-1-Web-Backend-Foundations.md)**

Move from standalone Python programs to applications that communicate over the web.

## Main Topics

- Client-server architecture
- Frontend vs backend
- HTTP requests and responses
- URLs
- HTTP methods
- Status codes
- Headers
- Query parameters
- Request bodies
- JSON
- Serialization
- APIs
- REST
- API consumption with Python
- Environment variables
- Endpoint testing

## Logic Focus

Learners reason about problems such as:

```text
Transport fares
Route information
Trade quotations
Currency conversion
Fuel costs
Seat availability
Shipment tracking
Import duties
```

### Level Outcome

The learner should understand what happens between:

```text
Client
   ↓
HTTP Request
   ↓
Backend
   ↓
Business Logic
   ↓
HTTP Response
```

---

# Level 2 — Django Web Development

**[Open Level 2 →](Python-Backend-Level-2-Django-Web-Development.md)**

Apply backend concepts using Django.

## Main Topics

- Django projects
- Django apps
- MVT architecture
- Settings
- URL routing
- Views
- Models
- Migrations
- Templates
- Forms
- ModelForms
- Validation
- Django Admin
- CRUD
- Application organization

## Logic Focus

Learners model systems involving:

```text
Routes
Vehicles
Trips
Passengers
Bookings
Products
Suppliers
Purchases
Sales
Shipments
```

### Level Outcome

The learner should be able to translate a business domain into Django models, views, forms and application logic.

---

# Level 3 — PostgreSQL & REST API Development

**[Open Level 3 →](Python-Backend-Level-3-PostgreSQL-REST-APIs.md)**

Move from basic Django applications to database-backed REST APIs.

## Main Topics

- PostgreSQL
- Relational databases
- Primary and foreign keys
- Constraints
- Django ORM
- QuerySets
- Relationships
- Query optimization
- Django REST Framework
- Serializers
- API views
- Generic views
- ViewSets
- Routers
- CRUD APIs
- Pagination
- Filtering
- API validation

## Logic Focus

Learners build APIs for:

```text
Freight quotations
International trade orders
Suppliers
Products
Shipments
Routes
Purchase orders
Inventory
```

### Level Outcome

The learner should be able to design and implement a relational PostgreSQL-backed REST API.

---

# Level 4 — Authentication, Security & Testing

**[Open Level 4 →](Python-Backend-Level-4-Authentication-Security-Testing.md)**

Develop backend systems that do not merely work, but enforce trust boundaries and remain correct as requirements change.

## Main Topics

- Authentication
- Authorization
- Django users
- Roles
- Permissions
- Object ownership
- Sessions
- Tokens
- JWT concepts
- Password security
- HTTPS
- CSRF
- CORS
- XSS
- SQL injection
- Secrets management
- Input validation
- Unit tests
- API tests
- Authorization tests

## Logic Focus

Learners reason about questions such as:

```text
Who owns this resource?
Who may view it?
Who may modify it?
Which actions require approval?
What should happen when access is denied?
What data should never be exposed?
```

### Level Outcome

The learner should be able to secure and test a backend rather than relying on authentication alone.

---

# Level 5 — Production Backend Engineering

**[Open Level 5 →](Python-Backend-Level-5-Production-Backend-Engineering.md)**

Advance from a working backend to a production-style system.

## Main Topics

- Production architecture
- Django deployment
- WSGI
- ASGI
- Docker
- PostgreSQL deployment
- Caching
- Redis concepts
- Background tasks
- Celery concepts
- Database performance
- Logging
- Health checks
- Monitoring
- CI/CD
- Failure handling
- Framework trade-offs
- FastAPI exposure

## Logic Focus

Learners investigate production problems such as:

```text
Peak transport demand
Slow report generation
Database failure
Cache failure
External API timeouts
Large datasets
Background jobs
Application restarts
```

### Level Outcome

The learner should understand how to make a backend deployable, observable, maintainable and resilient.

---

# Technology Progression

```text
Python
  ↓
HTTP
  ↓
JSON
  ↓
REST
  ↓
Django
  ↓
PostgreSQL
  ↓
Django ORM
  ↓
Django REST Framework
  ↓
Authentication & Permissions
  ↓
Automated Testing
  ↓
Docker
  ↓
Caching & Background Tasks
  ↓
CI/CD
  ↓
Deployment & Monitoring
```

---

# Learning Method

Backend competence cannot be developed through video consumption alone.

Each level follows:

```text
WATCH
   ↓
READ DOCUMENTATION
   ↓
UNDERSTAND CONCEPT
   ↓
REASON ABOUT PROBLEM
   ↓
DESIGN SOLUTION
   ↓
IMPLEMENT
   ↓
TEST
   ↓
BREAK
   ↓
DEBUG
   ↓
REFACTOR
   ↓
EXPLAIN
```

Learners should pause tutorials regularly and attempt implementation independently.

---

# Logic-Based Learning

Problems throughout the pathway use realistic domains such as:

- Economics
- Transport
- Logistics
- Trade
- Inventory
- Commerce
- Booking systems
- Business operations

For each backend problem, use:

```text
PROBLEM
   ↓
ACTORS
   ↓
INPUTS
   ↓
BUSINESS RULES
   ↓
DATA MODEL
   ↓
VALIDATION
   ↓
PROCESS
   ↓
OUTPUT
   ↓
FAILURE CASES
   ↓
SECURITY
   ↓
TESTS
```

The learner should be able to explain this logic before implementing it.

---

# Backend Engineering Principles

Throughout the pathway, learners should develop the habit of asking:

1. What problem is being solved?
2. Who is making the request?
3. What data is required?
4. Which data can be trusted?
5. Which business rules apply?
6. Where should the rule be enforced?
7. What should be stored?
8. What should be calculated?
9. What happens when something fails?
10. Who is allowed to perform this operation?
11. How will this behaviour be tested?
12. What happens when usage or data grows?

---

# Projects

Each level contains practical exercises and a competence challenge.

Projects become progressively more realistic:

```text
Level 1
Trade & Transport Service
        ↓
Level 2
Django Logistics Portal
        ↓
Level 3
Regional Trade & Logistics API
        ↓
Level 4
Secure Trade & Transport API
        ↓
Level 5
Regional Commerce & Logistics Backend
```

Later projects should build on competence developed in earlier levels rather than repeatedly starting from basic syntax.

---

# Final Competence Project

The final project requires a production-style backend for regional commerce and logistics.

Possible domains include:

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
Reports
Notifications
```

The learner must demonstrate competence in:

- Python
- HTTP
- backend architecture
- Django
- Django REST Framework
- PostgreSQL
- data modelling
- business logic
- validation
- authentication
- authorization
- testing
- security
- Docker
- deployment
- performance awareness
- logging and monitoring
- documentation

---

# Technical Defence

Code submission alone does not demonstrate competence.

Learners should be able to explain:

- how a request moves through the backend
- why particular models were created
- why relationships were selected
- where business rules are enforced
- how authentication works
- how authorization is enforced
- how invalid input is handled
- how failures are handled
- how database queries behave
- how the application is tested
- how the application is deployed
- what should be improved as the system grows

Assessors may modify requirements or introduce faults and require the learner to diagnose or extend the system.

---

# Competence Standard

Each level uses a **70% progression requirement**.

However, backend competence is not purely numerical.

Critical failures involving:

```text
Authorization
Security
Data integrity
Credential exposure
Fundamental business rules
```

must be corrected even when the learner's overall numerical mark exceeds the progression threshold.

---

# Recommended Repository Practice

Each competence project should contain:

```text
project/
├── application source
├── tests/
├── documentation/
├── .gitignore
├── .env.example
├── requirements.txt
└── README.md
```

Repositories should demonstrate meaningful Git history rather than a single final upload.

Never commit:

```text
.env
Passwords
API keys
Database credentials
Secret keys
Virtual environments
```

---

# Progress Tracker

## Level 1

- [ ] HTTP
- [ ] Client-server architecture
- [ ] JSON
- [ ] REST
- [ ] API reasoning
- [ ] Level 1 challenge
- [ ] Level 1 competence achieved

## Level 2

- [ ] Django architecture
- [ ] Models
- [ ] Migrations
- [ ] URLs and views
- [ ] Forms
- [ ] CRUD
- [ ] Level 2 challenge
- [ ] Level 2 competence achieved

## Level 3

- [ ] PostgreSQL
- [ ] Django ORM
- [ ] Relational modelling
- [ ] Django REST Framework
- [ ] Serializers
- [ ] REST APIs
- [ ] Query optimization
- [ ] Level 3 challenge
- [ ] Level 3 competence achieved

## Level 4

- [ ] Authentication
- [ ] Authorization
- [ ] Permissions
- [ ] Security
- [ ] Automated testing
- [ ] Authorization testing
- [ ] Level 4 challenge
- [ ] Level 4 competence achieved

## Level 5

- [ ] Docker
- [ ] Production configuration
- [ ] Performance
- [ ] Caching concepts
- [ ] Background tasks
- [ ] CI/CD
- [ ] Logging and monitoring
- [ ] Deployment
- [ ] Final competence project
- [ ] Technical defence

---

# Completion Standard

A learner completing this pathway should be able to receive an unfamiliar backend requirement and independently:

```text
Understand Requirements
        ↓
Identify Actors & Rules
        ↓
Model the Domain
        ↓
Design the Database
        ↓
Design the API
        ↓
Implement Business Logic
        ↓
Validate Input
        ↓
Secure Resources
        ↓
Test Behaviour
        ↓
Debug Failures
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
Defend Technical Decisions
```

> **Backend competence is not measured by how much Django syntax a learner remembers. It is demonstrated by the ability to turn requirements and business rules into secure, reliable, testable and maintainable server-side systems.**

---

## Start the Pathway

**[Begin Level 1 — Web & Python Backend Foundations →](Python-Backend-Level-1-Web-Backend-Foundations.md)**

---

**Beacon Innovation Hub — Learning Resources**  
*Python Backend Development Pathway

*<img width="5000" height="5000" alt="BEACON" src="https://github.com/user-attachments/assets/c69b5388-38d5-43e9-8c55-f47aba89f73f" />
