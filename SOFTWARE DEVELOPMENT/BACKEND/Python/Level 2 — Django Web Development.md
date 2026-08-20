# Level 2 — Django Web Development

> Learn Django as a structured backend framework and use it to model real business applications.

**Stage:** Backend Development  
**Prerequisite:** Level 1 — Web & Backend Foundations  
**Next:** Level 3 — PostgreSQL & REST API Development

---

## Learning Outcomes

- [ ] Create Django projects and apps
- [ ] Explain Django's MVT structure
- [ ] Configure URLs
- [ ] Write views
- [ ] Use templates
- [ ] Create models
- [ ] Run migrations
- [ ] Use Django Admin
- [ ] Build forms
- [ ] Validate input
- [ ] Perform CRUD operations
- [ ] Organize Django applications by business domain

---

# 1. Main Django Course

[![Python Django Web Framework](https://img.youtube.com/vi/F5mRW0jo-U4/maxresdefault.jpg)](https://www.youtube.com/watch?v=F5mRW0jo-U4)

**[▶ Python Django Web Framework — Full Course for Beginners](https://www.youtube.com/watch?v=F5mRW0jo-U4)**

The course covers:

```text
Virtual environments
Django project setup
Settings
Apps
Models
URLs
Requests
Templates
Forms
Validation
CRUD
Class-based views
```

Do not watch the entire course passively.

For every major section:

```text
WATCH
  ↓
CLOSE VIDEO
  ↓
REBUILD
  ↓
CHANGE REQUIREMENT
  ↓
DEBUG
```

---

# 2. Official Documentation

- [Django Documentation](https://docs.djangoproject.com/)
- [Django Tutorial](https://docs.djangoproject.com/en/stable/intro/tutorial01/)
- [Django Models](https://docs.djangoproject.com/en/stable/topics/db/models/)
- [Django Forms](https://docs.djangoproject.com/en/stable/topics/forms/)
- [Django URL Dispatcher](https://docs.djangoproject.com/en/stable/topics/http/urls/)

Use documentation as the primary technical reference.

---

# 3. Django Architecture

Understand:

```text
REQUEST
   ↓
URL
   ↓
VIEW
   ↓
MODEL / BUSINESS LOGIC
   ↓
TEMPLATE / RESPONSE
```

Learn:

- [ ] Project vs app
- [ ] `settings.py`
- [ ] `urls.py`
- [ ] `views.py`
- [ ] `models.py`
- [ ] `admin.py`
- [ ] migrations
- [ ] templates
- [ ] static files — introduction

---

# 4. Models & Migrations

A Django model represents persistent application data.

Example concept:

```text
Route
Vehicle
Trip
Passenger
Booking
```

Before writing models, identify:

```text
ENTITY
FIELDS
DATA TYPES
RELATIONSHIPS
CONSTRAINTS
BUSINESS RULES
```

Learn:

- [ ] `CharField`
- [ ] `IntegerField`
- [ ] `DecimalField`
- [ ] `BooleanField`
- [ ] `DateField`
- [ ] `DateTimeField`
- [ ] `ForeignKey`
- [ ] `OneToOneField`
- [ ] `ManyToManyField`

Understand:

```text
makemigrations
migrate
```

---

# 5. URLs & Views

Build URLs that represent clear application actions/resources.

Avoid meaningless routing such as:

```text
/doThing1/
```

Prefer:

```text
/routes/
routes/<id>/
bookings/
shipments/
```

Understand:

- function-based views
- class-based views — introduction
- route parameters
- reversing URLs
- namespacing

---

# 6. Templates

Learn:

- template inheritance
- variables
- loops
- conditions
- filters
- reusable partials

Do not place important business rules inside templates.

---

# 7. Forms & Validation

Learn:

- HTML forms
- Django forms
- ModelForms
- GET vs POST
- CSRF protection
- field validation
- custom validation
- displaying errors

---

# 8. Django Admin

Use Django Admin to inspect and manage application records during development.

Learn:

- registering models
- superusers
- list displays
- search
- filters

Understand that the admin interface is primarily an internal management tool, not automatically the customer-facing application.

---

# 9. Logic Lab — Public Transport Booking System

Build:

```text
Route
Vehicle
Trip
Passenger
Booking
```

Business rules:

```text
A vehicle has a capacity.
A trip uses one route.
A trip uses one vehicle.
A booking belongs to a trip.
Bookings cannot exceed vehicle capacity.
Cancelled bookings should release seats.
```

### Reasoning Questions

1. Where should seat availability be calculated?
2. Should `available_seats` be stored or calculated?
3. What happens if two users attempt to book the last seat?
4. Which model owns the booking status?

---

# 10. Logic Lab — Trade Inventory

Build:

```text
Product
Supplier
Purchase
Sale
```

Rules:

- stock cannot become negative
- selling price cannot be negative
- quantity must be positive
- sales reduce stock
- purchases increase stock

Do not solve these only in the template.

---

# 11. Practice Problems

## Problem 1 — Route Directory

Create list and detail pages for transport routes.

## Problem 2 — Shipment Form

Create a validated form for:

```text
Origin
Destination
Weight
Declared value
```

## Problem 3 — Trade Products

Create CRUD functionality for products.

## Problem 4 — Vehicle Assignment

Prevent an inactive vehicle from being assigned to a trip.

## Problem 5 — Booking Capacity

Reject bookings when no seats remain.

## Problem 6 — Search

Allow staff to search shipments or routes.

---

# Level 2 Challenge — Django Logistics Portal

Build a Django application for a transport/logistics company.

Required modules:

```text
accounts/
routes/
vehicles/
trips/
bookings/
shipments/
```

At this stage, Django's default development database may be used. PostgreSQL becomes mandatory in Level 3.

## Required Features

- models
- migrations
- admin
- URLs
- views
- templates
- forms
- CRUD
- validation
- reusable templates
- error pages

## Technical Defence

Explain:

1. Project vs app
2. Model vs form
3. URL vs view
4. Why this relationship is a ForeignKey
5. What a migration does
6. Why business logic should not live entirely in templates
7. How invalid bookings are prevented
8. How you would split a growing Django project

## Assessment

| Area | Weight |
|---|---:|
| Django architecture | 15% |
| Models/relationships | 20% |
| Views/URLs | 15% |
| Forms/validation | 15% |
| Business logic | 15% |
| Templates/UI integration | 10% |
| Code organization/documentation | 10% |

**Progression requirement: 70%**

[Continue to Level 3 →](Level%203%20—%20PostgreSQL%20%26%20REST%20API%20Development.md)
