# Clean Architecture in .NET

[![Clean Architecture in .NET](https://img.youtube.com/vi/yHf4pjy4pqE/maxresdefault.jpg)](https://youtu.be/yHf4pjy4pqE)

## Learning Resource

**Course:** Clean Architecture in .NET  
**Platform:** YouTube

[Watch the full tutorial](https://youtu.be/yHf4pjy4pqE)

---

## Topics Covered

- Clean Architecture
- Multi-Project Solution Structure
- Domain Layer
- Application Layer
- Infrastructure Layer
- Presentation Layer
- Enterprise Entities
- Value Objects
- Domain Logic
- Interface Contracts
- CQRS
- MediatR
- FastEndpoints
- Data Transfer Objects (DTOs)
- Request Validation
- Entity Framework Core
- Database Configuration
- External API Integration
- Authentication Integration
- Dependency Injection
- Blazor WebAssembly
- Blazor Server
- State Management

---

## 1. Architecture & Solution Setup

Clean Architecture is an approach to organizing software so that the application's core business logic is separated from external technologies and frameworks.

The project is divided into multiple layers, with each layer having a specific responsibility.

The solution follows a structure similar to:

```text
Solution
│
├── Domain
│
├── Application
│
├── Infrastructure
│
└── Presentation / UI
