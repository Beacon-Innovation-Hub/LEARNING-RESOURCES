# Level 4 — Authentication, Security & Testing

> Build backend systems that distinguish users, enforce permissions, validate untrusted input, protect sensitive data and remain correct as the codebase changes.

**Stage:** Intermediate → Advanced Backend  
**Prerequisite:** Level 3  
**Next:** Level 5 — Production Backend Engineering

---

## Learning Outcomes

- [ ] Explain authentication vs authorization
- [ ] Use Django's authentication system
- [ ] Implement role/permission rules
- [ ] Understand session, token and JWT approaches
- [ ] Protect secrets
- [ ] Apply API validation
- [ ] Understand common web/API threats
- [ ] Use CORS and CSRF correctly
- [ ] Write unit/integration/API tests
- [ ] Test authorization boundaries
- [ ] Build secure failure responses

---

# 1. Authentication & Permissions Video Resources

The DRF courses from Level 3 contain substantial authentication sections.

[![DRF Full Course](https://img.youtube.com/vi/dMCAHncMFQM/maxresdefault.jpg)](https://www.youtube.com/watch?v=dMCAHncMFQM)

**[▶ DRF Course — Token Authentication, Registration & Permissions](https://www.youtube.com/watch?v=dMCAHncMFQM)**

Focus on the chapters covering:

```text
Token authentication
Login
IsAuthenticated
Registration
Logout
Permissions
```

[![Django REST API Complete Tutorial](https://img.youtube.com/vi/c708Nf0cHrs/maxresdefault.jpg)](https://www.youtube.com/watch?v=c708Nf0cHrs)

**[▶ DRF Complete Tutorial — Authentication, Permissions & JWT](https://www.youtube.com/watch?v=c708Nf0cHrs)**

Relevant course sections include:

```text
Session authentication
Django model permissions
Custom permissions
Token authentication
JWT
CORS
```

---

# 2. Official Documentation

- [Django Authentication](https://docs.djangoproject.com/en/stable/topics/auth/)
- [Django Security](https://docs.djangoproject.com/en/stable/topics/security/)
- [DRF Authentication](https://www.django-rest-framework.org/api-guide/authentication/)
- [DRF Permissions](https://www.django-rest-framework.org/api-guide/permissions/)
- [DRF Testing](https://www.django-rest-framework.org/api-guide/testing/)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)

---

# 3. Authentication vs Authorization

```text
AUTHENTICATION
Who are you?

AUTHORIZATION
What are you allowed to do?
```

Do not confuse:

```text
logged in
```

with:

```text
allowed to perform every action
```

---

# 4. Roles & Permissions

Example transport platform:

```text
CUSTOMER
Create own booking
View own booking

DISPATCHER
View trips
Update shipment status

MANAGER
Manage routes
Manage vehicles
View financial reports

ADMINISTRATOR
System administration
```

Design permissions before implementing them.

---

# 5. Sessions, Tokens & JWT

Understand conceptually:

```text
Session authentication
Token authentication
JWT
```

For each compare:

- storage
- expiry
- revocation
- client usage
- risk
- appropriate use cases

Do not implement your own cryptographic authentication scheme.

---

# 6. Security Fundamentals

Study:

- [ ] Password hashing
- [ ] HTTPS
- [ ] CSRF
- [ ] XSS
- [ ] SQL injection
- [ ] CORS
- [ ] Input validation
- [ ] Secrets management
- [ ] Least privilege
- [ ] Sensitive logging
- [ ] Dependency risk
- [ ] Rate limiting — concept
- [ ] Brute-force protection — concept

Django provides important security protections, but developers can still create insecure systems through poor decisions.

---

# 7. Testing

Test at multiple levels:

```text
UNIT
Small function/business rule

MODEL
Model behaviour

API
Request → response

AUTHORIZATION
Who can perform action?

INTEGRATION
Multiple components working together
```

For APIs, test:

```text
200/201 success
400 invalid input
401 unauthenticated
403 forbidden
404 missing resource
```

---

# 8. Logic Lab — Transport Role System

Implement:

```text
Passenger
Driver
Dispatcher
Manager
```

Rules:

- passengers see only their own bookings
- drivers see assigned trips
- dispatchers update shipment/trip status
- managers create routes and view reports

### Attack Thinking

Try:

1. Passenger requests another passenger's booking.
2. Driver changes a route price.
3. Anonymous user creates a vehicle.
4. Dispatcher deletes a manager.

Every denied action should be tested.

---

# 9. Logic Lab — Trade Approval Workflow

Orders above a defined value require manager approval.

Example:

```text
Order < R10 000
→ standard processing

Order ≥ R10 000
→ manager approval required
```

Questions:

1. Who can approve?
2. Can the person creating the order approve it?
3. What happens after rejection?
4. Should the approval event be recorded?
5. What if the threshold changes?

---

# 10. Security Practice Problems

## Problem 1 — Object Ownership

Prevent one customer from retrieving another customer's order.

## Problem 2 — Role Escalation

Ensure ordinary users cannot assign themselves manager permissions.

## Problem 3 — Invalid Input

Attempt to submit extremely long strings, negative prices and unexpected fields.

## Problem 4 — Secret Exposure

Move all credentials and secret keys out of tracked source code.

## Problem 5 — Logging

Ensure logs provide useful diagnostics without recording passwords/tokens.

## Problem 6 — CORS

Explain why allowing every origin may be inappropriate for a production application.

---

# 11. Testing Challenge

For one API resource, create a test matrix:

| Scenario | Expected |
|---|---|
| Valid authenticated request | Success |
| Anonymous request | 401/appropriate denial |
| Wrong role | 403 |
| Missing resource | 404 |
| Invalid payload | 400 |
| Valid update | Success |
| Attempt to modify another user's resource | Denied |

Implement automated tests for the matrix.

---

# Level 4 Challenge — Secure Trade & Transport API

Extend the Level 3 API.

Required:

- users
- authentication
- roles
- permissions
- ownership rules
- protected financial operations
- input validation
- secret management
- security-aware logging
- automated API tests
- authorization tests

## Security Review

The assessor should attempt to:

```text
Access another user's data
Call protected endpoints anonymously
Escalate privileges
Submit malformed payloads
Modify protected fields
Expose secrets
Bypass workflow rules
```

## Technical Defence

Explain:

1. Authentication vs authorization
2. 401 vs 403
3. Why passwords are hashed
4. Why HTTPS matters
5. CSRF vs CORS
6. How SQL injection is reduced
7. How object ownership is enforced
8. What should never appear in logs
9. Why security tests are necessary
10. What happens if a token is stolen?

## Assessment

| Area | Weight |
|---|---:|
| Authentication | 15% |
| Authorization | 20% |
| Secure API design | 20% |
| Validation | 10% |
| Automated testing | 20% |
| Secrets/configuration | 5% |
| Security reasoning/defence | 10% |

**Progression requirement: 70%**

A critical authorization failure should require remediation even if the numerical mark exceeds 70%.

[Continue to Level 5 →](Level%205%20—%20Production%20Backend%20Engineering.md)
