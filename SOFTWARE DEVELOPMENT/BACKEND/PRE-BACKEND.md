# Backend Development Learning Path

> Learn how the web works before learning how to build the systems behind it.

![Level](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-success)
![Path](https://img.shields.io/badge/Path-Backend%20Development-blue)
![Learning](https://img.shields.io/badge/Approach-Practical-orange)

**Prerequisites:** Basic programming knowledge  
**Learning Model:** Understand → Watch → Read → Experiment → Build

---

## Backend Learning Roadmap

| Stage | Topic | Main Goal |
|---|---|---|
| 1 | Internet & Web Fundamentals | Understand how browsers, servers and the web communicate |
| 2 | HTTP & HTTPS | Understand web requests and responses |
| 3 | DNS & Networking | Understand how domains locate servers |
| 4 | Servers & Hosting | Understand where backend systems run |
| 5 | Backend Programming | Build server-side application logic |
| 6 | Databases & SQL | Store and retrieve persistent data |
| 7 | REST APIs | Build interfaces for applications |
| 8 | Authentication & Authorization | Control user access |
| 9 | Backend Security | Protect systems and data |
| 10 | Testing & API Testing | Verify backend behaviour |
| 11 | Caching & Performance | Improve application speed |
| 12 | Containers & Deployment | Package and deploy applications |
| 13 | Backend Architecture | Design maintainable systems |
| 14 | Real-World Projects | Apply the complete workflow |

---

# Level 1 — Internet & Web Foundations

**Level:** Beginner

Before building a backend application, you should understand what happens when a user enters a URL into a browser.

A simplified web request looks like:

```text
Browser
   ↓
DNS
   ↓
Server
   ↓
HTTP Request
   ↓
Backend Application
   ↓
Database / External Services
   ↓
HTTP Response
   ↓
Browser
```

By the end of this level, you should be able to explain every stage of this process.

---

# 1. HTTP Fundamentals

HTTP is the protocol used by clients and servers to communicate across the web.

## Main Video

[![HTTP Fundamentals](https://i.ytimg.com/vi/wW2A5SZ3GkI/hqdefault.jpg)](https://youtu.be/wW2A5SZ3GkI)

**[Watch: HTTP Fundamentals](https://youtu.be/wW2A5SZ3GkI)**

## Required Documentation

**[MDN — HTTP Overview](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Overview)**

## Learning Checklist

- [ ] What HTTP is
- [ ] Clients
- [ ] Servers
- [ ] Requests
- [ ] Responses
- [ ] URLs
- [ ] HTTP methods
- [ ] Headers
- [ ] Request bodies
- [ ] Response bodies
- [ ] HTTP status codes
- [ ] HTTP vs HTTPS

## HTTP Request Structure

```http
GET /api/students/42 HTTP/1.1
Host: example.com
Accept: application/json
```

## HTTP Response Structure

```http
HTTP/1.1 200 OK
Content-Type: application/json
```

```json
{
  "id": 42,
  "name": "Student Name"
}
```

---

# 2. HTTP Methods

| Method | Typical Purpose |
|---|---|
| `GET` | Retrieve data |
| `POST` | Create data |
| `PUT` | Replace data |
| `PATCH` | Update part of a resource |
| `DELETE` | Remove data |

## Practice

Consider:

```http
GET /api/students/42
```

Answer:

1. Who is the client?
2. Who is the server?
3. What does `GET` mean?
4. What does `/api/students/42` represent?
5. What could the backend do after receiving the request?
6. What might it retrieve from a database?
7. What should happen if student `42` does not exist?

---

# 3. HTTP Status Codes

```text
1xx → Information
2xx → Success
3xx → Redirection
4xx → Client Error
5xx → Server Error
```

## Practice

Explain:

```text
200
201
301
400
401
403
404
500
```

Then verify using:

**[MDN — HTTP Status Codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Status)**

---

# 4. DNS Fundamentals

```text
example.com
     ↓
DNS
     ↓
93.x.x.x
```

## Main Video

[![How DNS Works](https://i.ytimg.com/vi/mpQZVYPuDGU/hqdefault.jpg)](https://youtu.be/mpQZVYPuDGU)

**[Watch: How DNS Works](https://youtu.be/mpQZVYPuDGU)**

## Learning Checklist

- [ ] Domain names
- [ ] IP addresses
- [ ] DNS
- [ ] DNS resolvers
- [ ] Root servers
- [ ] TLD servers
- [ ] Authoritative name servers
- [ ] DNS caching
- [ ] DNS records

## DNS Resolution Flow

```text
User enters domain
       ↓
Browser checks cache
       ↓
DNS Resolver
       ↓
Root DNS Server
       ↓
TLD Server
       ↓
Authoritative DNS Server
       ↓
IP Address Returned
       ↓
Browser contacts server
```

## DNS Exercise

Explain what happens after entering:

```text
https://example.com
```

Your explanation should include:

```text
Domain
   ↓
DNS Lookup
   ↓
IP Address
   ↓
Server Connection
   ↓
HTTP Request
   ↓
HTTP Response
```

---

# 5. Servers & Web Hosting

## Main Video

[![Web Hosting](https://i.ytimg.com/vi/H8oAvyqQwew/hqdefault.jpg)](https://youtu.be/H8oAvyqQwew)

**[Watch: Web Hosting](https://youtu.be/H8oAvyqQwew)**

## Learning Checklist

- [ ] What a server is
- [ ] Web servers
- [ ] Application servers
- [ ] Hosting
- [ ] Shared hosting
- [ ] VPS hosting
- [ ] Dedicated servers
- [ ] Cloud hosting
- [ ] Domains
- [ ] Server resources
- [ ] Deployment

## Server Types

### Web Server

```text
HTTP Connection
      ↓
Static Files
      ↓
Reverse Proxy
      ↓
Application Server
```

Examples:

```text
Nginx
Apache
```

### Application Server

Examples:

```text
Django
Flask
FastAPI
Node.js
Spring
ASP.NET
```

---

# 6. Web Infrastructure

## Additional Video

[![Backend Web Fundamentals](https://i.ytimg.com/vi/EoYkl8rwbiM/hqdefault.jpg)](https://youtu.be/EoYkl8rwbiM)

**[Watch: Backend Web Fundamentals](https://youtu.be/EoYkl8rwbiM)**

---

# 7. Inspect Real HTTP Traffic

Open:

```text
Developer Tools
      ↓
Network
      ↓
Reload Page
```

Investigate:

- [ ] Request URL
- [ ] Request method
- [ ] Status code
- [ ] Request headers
- [ ] Response headers
- [ ] Response body
- [ ] Content type
- [ ] Request timing

---

# 8. Request Investigation Lab

Create a report containing:

```text
Request URL:
Request Method:
Status Code:
Content Type:
Request Headers:
Response Headers:
Response Size:
Request Duration:
```

Then explain:

> What did the browser request and what did the server return?

---

# 9. Full Web Request Challenge

Explain what happens when a user visits:

```text
https://example.com/students
```

Use:

```text
User
 ↓
Browser
 ↓
DNS
 ↓
IP Address
 ↓
Server
 ↓
HTTP Request
 ↓
Backend Application
 ↓
Database
 ↓
Backend Application
 ↓
HTTP Response
 ↓
Browser
```

---

# 10. Foundation Logic Challenge

Assume a user opens:

```text
https://example.com/api/products/123
```

The backend receives:

```http
GET /api/products/123
```

Think through:

```text
Request Received
      ↓
Validate Request
      ↓
Find Product 123
      ↓
Product Exists?
   ┌──────┴──────┐
  Yes            No
   ↓              ↓
Return Data     Return 404
   ↓
HTTP Response
```

Explain:

1. Where the product information might be stored.
2. What the backend should do if the database is unavailable.
3. Which status code should be returned when the product exists.
4. Which status code should be returned when it does not exist.
5. What format could be used for the response.

---

# Level 1 Progress Checklist

## Web Architecture

- [ ] Explain client-server architecture
- [ ] Explain how browsers communicate with servers
- [ ] Explain what happens when a URL is entered

## HTTP

- [ ] Explain HTTP
- [ ] Explain requests and responses
- [ ] Explain HTTP methods
- [ ] Explain status codes
- [ ] Explain headers
- [ ] Explain request and response bodies
- [ ] Explain HTTP vs HTTPS

## DNS & Networking

- [ ] Explain DNS
- [ ] Explain domain names
- [ ] Explain IP addresses
- [ ] Explain DNS caching

## Servers

- [ ] Explain what servers do
- [ ] Explain web servers
- [ ] Explain application servers
- [ ] Explain hosting
- [ ] Explain deployment

## Practical Skills

- [ ] Inspect HTTP traffic using DevTools
- [ ] Identify request methods
- [ ] Identify HTTP status codes
- [ ] Inspect headers
- [ ] Inspect response bodies
- [ ] Explain a complete web request lifecycle

---

# Level 1 Outcome

```text
User Action
     ↓
URL
     ↓
DNS Resolution
     ↓
Server Connection
     ↓
HTTP Request
     ↓
Backend Processing
     ↓
Database / Services
     ↓
HTTP Response
     ↓
Browser
```

---

# Next Level

## Level 2 — Backend Programming & APIs

```text
Python Backend Programming
        ↓
Backend Framework
        ↓
Routing
        ↓
Request Handling
        ↓
JSON
        ↓
REST APIs
        ↓
Database Integration
```

> Do not rush into a backend framework until you understand what the framework is actually doing on your behalf.
