# Level 3 — PostgreSQL & REST API Development

> Build database-backed REST APIs using Django, PostgreSQL and Django REST Framework.

**Stage:** Intermediate Backend  
**Prerequisite:** Level 2 — Django Web Development  
**Next:** Level 4 — Authentication, Security & Testing

---

## Learning Outcomes

- [ ] Use PostgreSQL with Django
- [ ] Design relational data models
- [ ] Use Django ORM effectively
- [ ] Explain lazy QuerySets
- [ ] Build REST APIs with Django REST Framework
- [ ] Create serializers
- [ ] Validate API input
- [ ] Build CRUD endpoints
- [ ] Use generic views and ViewSets
- [ ] Implement pagination/filtering
- [ ] Model relationships in API responses
- [ ] Identify inefficient database access

---

# 1. Django REST Framework Course

[![Django REST Framework Full Course 2026](https://img.youtube.com/vi/dMCAHncMFQM/maxresdefault.jpg)](https://www.youtube.com/watch?v=dMCAHncMFQM)

**[▶ Django REST Framework Full Course — Beginner to Pro (2026)](https://www.youtube.com/watch?v=dMCAHncMFQM)**

Topics include:

```text
REST
JSON
Models
Serializers
Serialization
Deserialization
CRUD
API views
Generic views
Token authentication basics
Permissions
Pagination
```

---

# 2. Additional DRF Project Course

[![Django REST API Complete Tutorial](https://img.youtube.com/vi/c708Nf0cHrs/maxresdefault.jpg)](https://www.youtube.com/watch?v=c708Nf0cHrs)

**[▶ Build a Django REST API — Complete Tutorial](https://www.youtube.com/watch?v=c708Nf0cHrs)**

Use this as a second implementation reference.

It includes:

- API clients
- serializers
- generic views
- permissions
- ViewSets
- routers
- related fields
- pagination
- JWT
- CORS

---

# 3. Official Documentation

- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [Django Database Documentation](https://docs.djangoproject.com/en/stable/topics/db/)
- [Django QuerySets](https://docs.djangoproject.com/en/stable/topics/db/queries/)
- [Django REST Framework](https://www.django-rest-framework.org/)
- [DRF Serializers](https://www.django-rest-framework.org/api-guide/serializers/)
- [DRF Views](https://www.django-rest-framework.org/api-guide/views/)

---

# 4. PostgreSQL

Learn:

- databases
- schemas
- tables
- rows
- columns
- primary keys
- foreign keys
- constraints
- indexes
- transactions
- SQL basics

Understand the relationship:

```text
Django Model
      ↓
Migration
      ↓
PostgreSQL Table
```

Do not rely on the ORM without understanding what the database is doing.

---

# 5. Django ORM

Practice:

```python
Model.objects.all()
Model.objects.get(...)
Model.objects.filter(...)
Model.objects.exclude(...)
Model.objects.create(...)
```

Learn:

- QuerySets
- lookups
- ordering
- aggregation
- annotations — introduction
- relationships
- `select_related()`
- `prefetch_related()`
- transactions — introduction

---

# 6. REST API Design

Example:

```text
GET    /api/routes/
POST   /api/routes/
GET    /api/routes/42/
PATCH  /api/routes/42/
DELETE /api/routes/42/
```

For every endpoint define:

```text
Purpose
Method
Path
Input
Validation
Output
Status Codes
Permissions
Failure Cases
```

---

# 7. Serializers

Understand that serializers are not simply "JSON converters."

They also help define:

- representation
- deserialization
- validation
- create/update behaviour

Practice:

```text
Serializer
ModelSerializer
Field validation
Object-level validation
Nested/related representation
```

---

# 8. Logic Lab — Freight Quote API

Create:

```text
POST /api/freight-quotes/
```

Inputs:

```text
Origin
Destination
Distance
Weight
Priority
Declared value
```

Business rules may include:

```text
Base transport rate
Weight surcharge
Express surcharge
Insurance percentage
```

Return a detailed quote.

### Higher-Order Questions

1. Should the client provide distance?
2. Which fields should be calculated server-side?
3. Should quotes be stored?
4. What happens if pricing rules change after a quote is issued?

---

# 9. Logic Lab — International Trade Orders

Models:

```text
Supplier
Product
PurchaseOrder
PurchaseOrderItem
Shipment
```

Requirements:

- one order can contain multiple products
- each item has quantity and agreed unit cost
- order totals are calculated
- shipment status is tracked
- invalid foreign keys must be rejected

---

# 10. API Practice Problems

## Problem 1 — Routes API

Implement list, create, retrieve, update and delete.

## Problem 2 — Shipment Filtering

Support:

```text
/api/shipments/?status=delayed
```

## Problem 3 — Pagination

Return large order collections in pages.

## Problem 4 — Validation

Reject:

```text
negative quantity
negative price
invalid status
unknown route
```

## Problem 5 — Relationship API

Return a purchase order with its line items.

## Problem 6 — Query Efficiency

Identify and correct an N+1 query problem.

---

# 11. API Testing Practice

Test endpoints using:

- DRF Browsable API
- curl
- an API client such as Postman

For every endpoint test:

```text
Valid request
Missing field
Invalid field
Unknown resource
Empty result
Duplicate request
Unexpected data type
```

---

# Level 3 Challenge — Regional Trade & Logistics API

Build a PostgreSQL-backed REST API containing:

```text
/api/suppliers/
/api/products/
/api/orders/
/api/shipments/
/api/routes/
/api/freight-quotes/
```

## Required Features

- PostgreSQL
- relational models
- migrations
- serializers
- CRUD
- validation
- pagination
- filtering
- correct status codes
- optimized relationship queries
- API documentation in README

## Technical Defence

Explain:

1. Why PostgreSQL?
2. What does the ORM generate?
3. When would an index help?
4. What is an N+1 query?
5. Why use `select_related()`?
6. Serializer vs model
7. PUT vs PATCH
8. 400 vs 404 vs 409
9. How relationships are represented
10. What happens when the dataset grows?

## Assessment

| Area | Weight |
|---|---:|
| PostgreSQL/data modelling | 20% |
| Django ORM | 15% |
| REST design | 15% |
| DRF implementation | 20% |
| Validation/error handling | 10% |
| Query efficiency | 10% |
| Testing/documentation | 10% |

**Progression requirement: 70%**

[Continue to Level 4 →](Level%204%20—%20Authentication%2C%20Security%20%26%20Testing.md)
