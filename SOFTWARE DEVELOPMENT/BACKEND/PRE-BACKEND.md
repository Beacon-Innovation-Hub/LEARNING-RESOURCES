# ⚙️ Backend Development Learning Path

> Learn how the web works before learning how to build the systems behind it.

**Level:** 🟢 Beginner → 🔴 Advanced  
**Prerequisites:** Basic programming knowledge  
**Learning Model:** Understand → Watch → Read → Experiment → Build

---

# 📍 Backend Learning Roadmap

1. Internet & Web Fundamentals
2. HTTP & HTTPS
3. DNS & Networking Fundamentals
4. Servers, Hosting & Deployment
5. Backend Programming
6. Databases & SQL
7. REST APIs
8. Authentication & Authorization
9. Backend Security
10. Testing & API Testing
11. Caching & Performance
12. Containers & Deployment
13. Backend Architecture
14. Real-World Backend Projects

---

# 1. Internet & Web Fundamentals

**Level:** 🟢 Beginner

Before building a backend, understand what actually happens when a user
enters a URL into their browser.

A backend developer should be able to explain:

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
Database / Services
   ↓
HTTP Response
   ↓
Browser

---

# 🌐 HTTP Fundamentals

[![HTTP Fundamentals](https://img.youtube.com/vi/wW2A5SZ3GkI/maxresdefault.jpg)](https://youtu.be/wW2A5SZ3GkI)

## 🎥 Video Resource

**[▶ Watch HTTP Fundamentals](https://youtu.be/wW2A5SZ3GkI)**

## 📚 Required Documentation

**[📘 MDN — HTTP Overview](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Overview)**

## 🎯 Understand

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

---

# 🌍 DNS

[![How DNS Works](https://img.youtube.com/vi/mpQZVYPuDGU/maxresdefault.jpg)](https://youtu.be/mpQZVYPuDGU)

## 🎥 Video Resource

**[▶ Watch: How DNS Works](https://youtu.be/mpQZVYPuDGU)**

DNS translates human-readable domain names into IP addresses that
computers can use to communicate.

## 🎯 Understand

- [ ] Domain names
- [ ] IP addresses
- [ ] DNS
- [ ] DNS resolver
- [ ] Root servers
- [ ] TLD servers
- [ ] Authoritative name servers
- [ ] DNS caching
- [ ] DNS records

## 🧩 Exercise

Explain what happens after entering:

https://example.com

into a browser.

Your explanation should include:

Domain
   ↓
DNS lookup
   ↓
IP address
   ↓
Server connection
   ↓
HTTP request
   ↓
HTTP response

---

# 🖥️ Servers & Web Hosting

[![Web Hosting](https://img.youtube.com/vi/H8oAvyqQwew/maxresdefault.jpg)](https://youtu.be/H8oAvyqQwew)

## 🎥 Video Resource

**[▶ Watch: Web Hosting](https://youtu.be/H8oAvyqQwew)**

## 🎯 Understand

- [ ] What a server is
- [ ] Web servers
- [ ] Application servers
- [ ] Hosting
- [ ] Shared hosting
- [ ] VPS
- [ ] Dedicated servers
- [ ] Cloud hosting
- [ ] Domains
- [ ] Server resources
- [ ] Deployment

---

# 🌐 Additional Web Infrastructure Resource

[![Backend Web Fundamentals](https://img.youtube.com/vi/EoYkl8rwbiM/maxresdefault.jpg)](https://youtu.be/EoYkl8rwbiM)

**[▶ Watch the Resource](https://youtu.be/EoYkl8rwbiM)**

Use this resource alongside the previous lessons to strengthen your
understanding of how web infrastructure works.

---

# 🧪 Interactive Practice

Do not only watch the videos.

Open your browser's Developer Tools.

Go to:

Network → Reload Page

Select one of the requests and investigate:

- [ ] Request URL
- [ ] Request method
- [ ] Status code
- [ ] Request headers
- [ ] Response headers
- [ ] Response body
- [ ] Content type
- [ ] Request timing

Try this on several different websites.

---

# 🧩 HTTP Exercise

Without looking up the answers first, explain what these status codes
represent:

200
201
301
400
401
403
404
500

Then verify your answers using MDN documentation.

---

# 🧩 Request/Response Exercise

Consider:

GET /api/students/42

Explain:

1. Who is the client?
2. Who is the server?
3. What does GET mean?
4. What does `/api/students/42` represent?
5. What could the backend do after receiving this request?
6. What might it retrieve from a database?
7. What should happen if student 42 does not exist?

---

# 🧩 Full Web Request Challenge

Draw the complete process that occurs when a user visits:

https://example.com/students

Your diagram should include:

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
Backend
 ↓
Database
 ↓
Backend
 ↓
HTTP Response
 ↓
Browser

Explain every step in your own words.

---

# ✅ Foundation Progress

Before moving into backend programming:

- [ ] I understand client/server architecture
- [ ] I understand HTTP
- [ ] I understand requests and responses
- [ ] I understand HTTP methods
- [ ] I understand status codes
- [ ] I understand DNS
- [ ] I understand domains and IP addresses
- [ ] I understand what servers do
- [ ] I understand basic hosting
- [ ] I can inspect HTTP traffic using browser DevTools
- [ ] I can explain what happens when a URL is entered into a browser

> Do not rush into a backend framework until you understand what the
> framework is actually doing for you.
