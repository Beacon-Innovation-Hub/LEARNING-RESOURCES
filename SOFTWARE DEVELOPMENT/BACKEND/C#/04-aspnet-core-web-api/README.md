# ASP.NET Core Web API

[![ASP.NET Core Web API Tutorial](https://img.youtube.com/vi/RwQVRXEs370/maxresdefault.jpg)](https://youtu.be/RwQVRXEs370)

## Learning Resource

**Course:** ASP.NET Core Web API Tutorial  
**Platform:** YouTube

[Watch the full tutorial](https://youtu.be/RwQVRXEs370)

---

## Topics Covered

- ASP.NET Core Web API
- Controller-Based Architecture
- Project Setup
- Domain Models
- Entity Framework Core
- `DbContext`
- SQL Server
- Connection Strings
- EF Core Migrations
- API Controllers
- Routing
- HTTP Methods
- `GET`
- `POST`
- `PUT`
- `DELETE`
- Data Transfer Objects (DTOs)
- Dependency Injection
- CRUD Operations
- Asynchronous Programming
- `ToListAsync()`
- `FindAsync()`
- `SaveChangesAsync()`
- Swagger/OpenAPI
- Postman
- API Testing

---

## 1. Introduction & Project Setup

ASP.NET Core Web API is a framework for building HTTP-based services and RESTful APIs using C# and .NET.

In this section, a new ASP.NET Core Web API project is created using a **controller-based architecture**.

### Controller-Based Architecture

Controllers are responsible for handling incoming HTTP requests and returning appropriate responses.

A simplified API structure looks like:

```text
Client
   ↓
HTTP Request
   ↓
Controller
   ↓
Application Logic
   ↓
Database
   ↓
HTTP Response
   ↓
Client
