# 🅰️ Angular Learning Path

> Learn Angular by understanding components, templates, TypeScript, dependency injection, forms, routing, APIs, reactive programming, and real-world application architecture.

**Level:** 🟢 Beginner → 🔴 Advanced
**Prerequisites:** HTML, CSS, JavaScript & TypeScript fundamentals
**Learning Model:** Watch → Read → Experiment → Practice → Build

---

# ⚠️ Before Starting Angular

Angular relies heavily on JavaScript and TypeScript.

Before beginning, you should understand:

* [ ] HTML
* [ ] CSS
* [ ] JavaScript variables and functions
* [ ] Arrays and objects
* [ ] ES modules
* [ ] Classes
* [ ] Promises
* [ ] `async` / `await`
* [ ] APIs
* [ ] TypeScript fundamentals
* [ ] Interfaces
* [ ] Types
* [ ] Classes in TypeScript

If these concepts are unfamiliar, complete the relevant JavaScript and TypeScript learning material first.

---

# 📍 Learning Path

1. [Angular Foundations](#1-angular-foundations)
2. [Components, Templates & Data Binding](#2-components-templates--data-binding)
3. [Directives, Control Flow & Pipes](#3-directives-control-flow--pipes)
4. [Angular Forms](#4-angular-forms)
5. [Services & Dependency Injection](#5-services--dependency-injection)
6. [Routing & Application Structure](#6-routing--application-structure)
7. [HTTP, APIs & Reactive Programming](#7-http-apis--reactive-programming)
8. [Signals & Modern Angular Reactivity](#8-signals--modern-angular-reactivity)
9. [Professional Angular](#9-professional-angular)
10. [Real-World Angular Projects](#10-real-world-angular-projects)

---

# 🎥 Full Angular Course

Use the following playlist as a supporting course throughout this learning path.

**[▶ Open Complete Angular Tutorial Playlist](https://www.youtube.com/playlist?list=PLC3y8-rFHvwhwL-XH04cHOpJnkgRKykFi)**

Do not watch the entire playlist before practising.

Use:

```text
Video
  ↓
Official Documentation
  ↓
Experiment
  ↓
Exercise
  ↓
Small Project
```

> Some video resources may demonstrate older Angular syntax. When a video differs from current Angular documentation, follow the current Angular documentation.

---

# 1. Angular Foundations

**Level:** 🟢 Beginner

[![Angular Tutorial for Beginners](https://img.youtube.com/vi/k5E2AVpwsko/maxresdefault.jpg)](https://youtu.be/k5E2AVpwsko)

## 🎥 Beginner Resource

**[▶ Watch Angular Tutorial for Beginners](https://youtu.be/k5E2AVpwsko)**

---

## 🎯 Learn

* What Angular is
* Single-page applications
* Angular project structure
* TypeScript in Angular
* Angular CLI
* Components
* Templates
* Component styles
* Application bootstrapping
* Basic data binding
* Events
* Rendering dynamic information

---

# 📚 Official Angular Learning

## Angular Tutorial

**[📘 Learn Angular](https://angular.dev/tutorials/learn-angular)**

## Angular Essentials

**[📘 Angular Essentials](https://angular.dev/essentials)**

Use the official interactive lessons alongside the videos.

---

# 🧪 Practice

* [ ] Create an Angular project
* [ ] Run the development server
* [ ] Explore the project structure
* [ ] Create your first component
* [ ] Display text
* [ ] Display dynamic data
* [ ] Add component styles
* [ ] Handle a button click

---

# 🧩 First Angular Challenge

Create a:

```text
StudentProfile
```

component.

Display:

* Student name
* Course
* Year
* Skills
* Profile image
* Short biography

Do not hard-code everything directly into the template.

Store appropriate information in the component class and render it in the template.

---

# 2. Components, Templates & Data Binding

**Level:** 🟢 Beginner → 🟡 Intermediate

Angular applications are composed of components.

Each component combines behavior, a template, and presentation.

---

## 🎥 Components & Templates

[![Angular Components and Templates](https://img.youtube.com/vi/zraDrkVyZ_k/maxresdefault.jpg)](https://youtu.be/zraDrkVyZ_k)

**[▶ Watch Angular Components & Templates](https://youtu.be/zraDrkVyZ_k)**

---

# 📚 Official Documentation

**[📘 Angular Components](https://angular.dev/guide/components)**

**[📘 Angular Templates](https://angular.dev/guide/templates)**

---

## 🎯 Learn

* Components
* Component classes
* Templates
* Component selectors
* Component styles
* Component composition
* Parent components
* Child components
* Inputs
* Outputs
* Template expressions
* Events
* Dynamic data

---

# 🔗 Property Binding

[![Angular Property Binding](https://img.youtube.com/vi/N8FBmB2jme8/maxresdefault.jpg)](https://youtu.be/N8FBmB2jme8)

**[▶ Watch Angular Property Binding](https://youtu.be/N8FBmB2jme8)**

---

## 🎯 Understand

* Interpolation
* Property binding
* Event binding
* Dynamic properties
* HTML attributes vs DOM properties
* Binding images
* Binding button states
* Dynamic classes
* Dynamic styles

---

# 🧪 Binding Practice

Create a product:

```typescript
product = {
    name: 'Laptop',
    price: 12000,
    image: 'assets/laptop.jpg',
    available: true
};
```

Use Angular binding to:

* [ ] Display the product name
* [ ] Display the price
* [ ] Bind the image
* [ ] Disable a button when unavailable
* [ ] Change styling depending on availability
* [ ] Handle an Add to Cart event

---

# 🧩 Component Practice

Build:

* [ ] `Header`
* [ ] `Navbar`
* [ ] `ProfileCard`
* [ ] `ProductCard`
* [ ] `Footer`

Then combine them into one application.

---

# 3. Directives, Control Flow & Pipes

**Level:** 🟡 Intermediate

[![Angular Components Directives and Pipes](https://img.youtube.com/vi/23o0evRtrFI/maxresdefault.jpg)](https://youtu.be/23o0evRtrFI)

## 🎥 Resource

**[▶ Watch Components, Directives & Pipes](https://youtu.be/23o0evRtrFI)**

---

## 🎯 Learn

* Angular control flow
* Conditional rendering
* Rendering collections
* Directives
* Attribute directives
* Dynamic classes
* Dynamic styles
* Pipes
* Built-in pipes
* Custom pipes

---

# 📚 Official Documentation

**[📘 Angular Templates](https://angular.dev/guide/templates)**

**[📘 Angular Pipes](https://angular.dev/guide/templates/pipes)**

---

# 🧪 Practice

Create a product catalogue.

Each product should contain:

```text
Name
Price
Category
Stock
Date Added
```

Practice:

* [ ] Render multiple products
* [ ] Conditionally show availability
* [ ] Format prices
* [ ] Format dates
* [ ] Apply dynamic styling
* [ ] Filter displayed information
* [ ] Create a custom pipe

---

# 4. Angular Forms

**Level:** 🟡 Intermediate

Forms are essential for collecting and validating user input.

Angular supports multiple approaches to building forms.

---

## 🎥 Form / Binding Resource

[![Angular Forms](https://img.youtube.com/vi/hAaoPOx_oIw/maxresdefault.jpg)](https://youtu.be/hAaoPOx_oIw)

**[▶ Watch Angular Form / Binding Resource](https://youtu.be/hAaoPOx_oIw)**

Use the full Angular playlist for additional form lessons.

---

# 📚 Official Forms Documentation

**[📘 Angular Forms](https://angular.dev/guide/forms)**

---

## 🎯 Learn

### Template-Driven Forms

* Forms
* Inputs
* Two-way binding
* Validation
* Form submission
* Error messages

### Reactive Forms

* `FormControl`
* `FormGroup`
* Validators
* Form state
* Dynamic forms
* Programmatic control
* Custom validation

---

# 🧩 Form Practice

Build:

* [ ] Login form
* [ ] Registration form
* [ ] Contact form
* [ ] Search form

---

# 🧪 Registration Challenge

Create:

```text
Full Name
Email
Password
Confirm Password
Role
Date of Birth
Terms & Conditions
Submit
```

Your form should:

* [ ] Validate required fields
* [ ] Validate email
* [ ] Validate password length
* [ ] Check matching passwords
* [ ] Display meaningful errors
* [ ] Prevent invalid submission
* [ ] Display successful submission

Build a simple version first.

Then rebuild it using Reactive Forms.

---

# 5. Services & Dependency Injection

**Level:** 🟡 Intermediate

Components should not contain every piece of application logic.

Angular services allow reusable logic and data access to be shared across the application.

---

# 📚 Official Documentation

**[📘 Angular Dependency Injection](https://angular.dev/guide/di)**

---

## 🎯 Learn

* Services
* Dependency injection
* Providers
* Injectors
* `inject()`
* Service responsibilities
* Sharing logic
* Sharing data
* Separating UI from application logic

---

# 🧩 Service Challenge

Create:

```text
ProductService
```

The service should provide product information to multiple components.

Your application should contain:

```text
ProductService
       ↓
ProductList
       ↓
ProductCard
```

Avoid duplicating the product data across components.

---

# 🧩 Second Challenge

Create:

```text
NotificationService
```

Allow different components to trigger application notifications.

Examples:

```text
Product added
Form submitted
Login successful
Operation failed
```

---

# 6. Routing & Application Structure

**Level:** 🟡 Intermediate

Routing allows users to navigate between different application views.

---

# 📚 Angular Router

**[📘 Angular Routing](https://angular.dev/guide/routing)**

Use the routing lessons in the full Angular playlist as additional video support.

---

## 🎯 Learn

* Angular Router
* Routes
* Router outlet
* Navigation
* Route parameters
* Query parameters
* Nested routes
* Child routes
* Route guards
* Lazy loading
* 404 routes

---

# 🧩 Routing Exercise

Create:

```text
/
├── Home
├── About
├── Products
│   └── /products/:id
├── Contact
└── 404
```

The Product Detail page should determine which product to display using the route parameter.

---

# 🏗️ Application Structure

As applications grow, organize functionality intentionally.

Example:

```text
src/app/
│
├── components/
│   ├── navbar/
│   ├── footer/
│   └── product-card/
│
├── pages/
│   ├── home/
│   ├── products/
│   ├── product-detail/
│   └── contact/
│
├── services/
│   └── product.service.ts
│
├── models/
│   └── product.ts
│
└── app.routes.ts
```

Do not copy a folder structure simply because another application uses it.

Structure should reflect the needs of your application.

---

# 7. HTTP, APIs & Reactive Programming

**Level:** 🟡 Intermediate → 🔴 Advanced

Modern Angular applications frequently communicate with backend APIs.

---

# 📚 HTTP Documentation

**[📘 Angular HTTP Client](https://angular.dev/guide/http)**

---

## 🎯 Learn

* `HttpClient`
* HTTP requests
* GET
* POST
* PUT
* PATCH
* DELETE
* JSON
* Request parameters
* Headers
* Error handling
* Loading states
* API services
* Interceptors

---

# 🧩 API Exercise

Create:

```text
UserService
```

Fetch users from an API.

Display:

* Name
* Email
* Username
* Company

Handle:

```text
Loading
     ↓
Success
     ↓
Empty Results
     ↓
Error
```

---

# 🔄 Reactive Programming

Angular applications commonly use reactive programming concepts.

Learn:

* Observables
* Subscriptions
* Operators
* Streams
* Transforming data
* Error handling
* Async data
* RxJS fundamentals

---

# 🧪 Reactive Exercises

* [ ] Create an Observable
* [ ] Subscribe to an Observable
* [ ] Transform values
* [ ] Filter values
* [ ] Handle errors
* [ ] Work with HTTP Observables
* [ ] Display async API data
* [ ] Search API results reactively

---

# 🧩 Search Challenge

Create a product search interface.

```text
User types
    ↓
Search input
    ↓
Process search
    ↓
API/service
    ↓
Results
```

Avoid unnecessary requests.

Handle:

* [ ] Empty search
* [ ] Loading
* [ ] Results
* [ ] No results
* [ ] Errors

---

# 8. Signals & Modern Angular Reactivity

**Level:** 🔴 Advanced

Modern Angular includes Signals for managing reactive state.

---

# 📚 Official Documentation

**[📘 Angular Signals](https://angular.dev/guide/signals)**

---

## 🎯 Learn

* `signal()`
* Reading signals
* Updating signals
* `computed()`
* `effect()`
* Derived state
* Reactive dependencies
* Signals in components
* Signals and RxJS

---

# 🧩 Counter Exercise

Create:

```typescript
count = signal(0);
```

Implement:

* [ ] Increment
* [ ] Decrement
* [ ] Reset

Then create a computed value:

```text
count × 2
```

Do not store the doubled value separately if it can be derived.

---

# 🧩 Shopping Cart Exercise

Store cart state using signals.

Calculate:

```text
Total Items
Total Price
```

as derived values.

Think carefully about:

> What information needs to be state, and what information can be computed?

---

# 9. Professional Angular

**Level:** 🔴 Advanced

The objective now changes from:

> Does the application work?

to:

> Is the application maintainable, testable, accessible, secure and scalable?

---

# 🧪 Testing

Angular provides testing tools for components, services, routing and HTTP behavior.

Study:

* Unit testing
* Component testing
* Service testing
* Dependency mocking
* User interaction testing
* Router testing
* HTTP testing
* Error-state testing

---

# 📚 Official Testing Documentation

**[📘 Angular Testing](https://angular.dev/guide/testing)**

---

## 🧩 Testing Practice

Write tests for:

* [ ] Calculator service
* [ ] Product service
* [ ] Button component
* [ ] Product card
* [ ] Form validation
* [ ] Route navigation
* [ ] API success
* [ ] API failure

---

# ♿ Accessibility

Angular still produces HTML.

Everything learned about accessibility in `html.md` remains relevant.

Review:

* [ ] Semantic HTML
* [ ] Accessible forms
* [ ] Labels
* [ ] Keyboard navigation
* [ ] Focus
* [ ] Alternative text
* [ ] Heading hierarchy
* [ ] Accessible navigation
* [ ] Appropriate ARIA usage

---

# 🐛 Debugging

Learn to use:

* Browser Developer Tools
* Angular DevTools
* Network panel
* Breakpoints
* Console
* Component inspection
* Dependency inspection
* Performance profiling

---

# 🔐 Security

Understand:

* User input cannot be trusted
* XSS fundamentals
* Angular sanitization
* Authentication concepts
* Authorization concepts
* API security boundaries
* Secret management
* Dependency security
* Safe DOM manipulation

Never place private secrets directly inside frontend Angular code.

---

# ⚡ Performance

Understand:

* Component rendering
* Change detection
* Signals
* Lazy loading
* Route-level loading
* Deferrable views
* Bundle size
* Image optimization
* Network performance

Measure before optimizing.

---

# 10. Real-World Angular Projects

At this stage, reduce dependence on tutorials.

Build applications from:

```text
Problem
   ↓
Requirements
   ↓
Design
   ↓
Architecture
   ↓
Implementation
   ↓
Testing
   ↓
Refactoring
```

---

# 🟢 Project 1 — Task Manager

Users should be able to:

* [ ] Create tasks
* [ ] Edit tasks
* [ ] Delete tasks
* [ ] Complete tasks
* [ ] Filter tasks

Use multiple components.

---

# 🟢 Project 2 — Student Management Interface

Create:

```text
Students
Courses
Marks
Search
Filtering
Forms
```

Practice:

* Components
* Services
* Forms
* Pipes
* Routing

---

# 🟡 Project 3 — Product Catalogue

Implement:

* [ ] Product list
* [ ] Product details
* [ ] Categories
* [ ] Search
* [ ] Filtering
* [ ] Routing
* [ ] Product service

---

# 🟡 Project 4 — API Dashboard

Build a dashboard that consumes an external API.

Implement:

* [ ] HTTP requests
* [ ] Services
* [ ] Loading states
* [ ] Error states
* [ ] Filtering
* [ ] Search
* [ ] Multiple views

---

# 🟡 Project 5 — Expense Tracker

Users should be able to:

* [ ] Add transactions
* [ ] Delete transactions
* [ ] Categorize expenses
* [ ] Calculate expenses
* [ ] Calculate income
* [ ] Calculate balance
* [ ] Filter transactions

---

# 🔴 Project 6 — E-Commerce Frontend

Build:

```text
Products
   ↓
Product Details
   ↓
Cart
   ↓
Checkout
```

Include:

* [ ] Routing
* [ ] Services
* [ ] Forms
* [ ] API integration
* [ ] Shared state
* [ ] Search
* [ ] Filtering
* [ ] Cart totals
* [ ] Error handling

---

# 🔴 Project 7 — Administration Dashboard

Build an administration application containing:

* [ ] Authentication-style interface
* [ ] Dashboard
* [ ] Users
* [ ] Search
* [ ] Filtering
* [ ] Sorting
* [ ] Forms
* [ ] Routing
* [ ] API integration
* [ ] Loading states
* [ ] Error states
* [ ] Shared application state
* [ ] Tests

---

# 🔴 Project 8 — Full Angular Application

Build a larger Angular application from an unfamiliar specification.

Possible structure:

```text
src/app/
│
├── core/
├── shared/
├── features/
├── services/
├── models/
├── guards/
├── interceptors/
│
├── app.routes.ts
└── app.ts
```

Do not treat this structure as mandatory.

Design your architecture based on the application requirements.

---

# 🎮 Interactive Angular Learning

## 🅰️ Official Angular Tutorial

**[🚀 Interactive Angular Tutorial](https://angular.dev/tutorials/learn-angular)**

Use the browser-based lessons to practise Angular concepts.

---

## ⚡ StackBlitz

**[🚀 StackBlitz](https://stackblitz.com/)**

Use StackBlitz to create and run Angular applications directly in your browser.

This is useful when you want to experiment without configuring a local project.

---

# 📊 Progress Checklist

## 🟢 Level 1 — Foundations

* [ ] Angular beginner tutorial
* [ ] Angular Essentials
* [ ] Angular CLI
* [ ] Project structure
* [ ] Components
* [ ] First Angular challenge

## 🟢 Level 2 — Components & Binding

* [ ] Components
* [ ] Templates
* [ ] Interpolation
* [ ] Property binding
* [ ] Event binding
* [ ] Inputs
* [ ] Outputs
* [ ] Component exercises

## 🟡 Level 3 — Templates

* [ ] Control flow
* [ ] Directives
* [ ] Pipes
* [ ] Dynamic classes
* [ ] Dynamic styles
* [ ] Product catalogue exercise

## 🟡 Level 4 — Forms

* [ ] Template-driven forms
* [ ] Two-way binding
* [ ] Validation
* [ ] Reactive Forms
* [ ] Custom validation
* [ ] Registration challenge

## 🟡 Level 5 — Services

* [ ] Services
* [ ] Dependency injection
* [ ] Providers
* [ ] `inject()`
* [ ] Product service
* [ ] Notification service

## 🟡 Level 6 — Routing

* [ ] Routes
* [ ] Navigation
* [ ] Parameters
* [ ] Nested routes
* [ ] Guards
* [ ] Lazy loading
* [ ] 404 route

## 🔴 Level 7 — HTTP & Reactive Programming

* [ ] `HttpClient`
* [ ] GET
* [ ] POST
* [ ] Error handling
* [ ] API services
* [ ] Observables
* [ ] RxJS fundamentals
* [ ] Search challenge

## 🔴 Level 8 — Signals

* [ ] `signal()`
* [ ] Updating signals
* [ ] `computed()`
* [ ] `effect()`
* [ ] Derived state
* [ ] Signals exercise

## 🔴 Level 9 — Professional Angular

* [ ] Testing
* [ ] Accessibility
* [ ] Debugging
* [ ] Security
* [ ] Performance
* [ ] Application architecture

## 🏗️ Projects

* [ ] Task Manager
* [ ] Student Management Interface
* [ ] Product Catalogue
* [ ] API Dashboard
* [ ] Expense Tracker
* [ ] E-Commerce Frontend
* [ ] Administration Dashboard
* [ ] Full Angular Application

---

# 🚀 Complete Angular Progression

```text
JavaScript + TypeScript
          ↓
🟢 Angular Foundations
          ↓
🟢 Components, Templates & Binding
          ↓
🟡 Directives, Control Flow & Pipes
          ↓
🟡 Forms
          ↓
🟡 Services & Dependency Injection
          ↓
🟡 Routing
          ↓
🔴 HTTP, APIs & RxJS
          ↓
🔴 Signals & Reactivity
          ↓
🔴 Professional Angular
          ↓
🏗️ Real-World Applications
```

---

# 💡 Learning Principle

Do not learn Angular by continuously following tutorials.

Use:

```text
🎥 Watch
    ↓
📚 Read Angular Documentation
    ↓
🧪 Experiment
    ↓
🧩 Solve
    ↓
🏗️ Build
    ↓
🐛 Debug
    ↓
🧪 Test
    ↓
🔁 Refactor
```

When stuck:

1. Read the error message.
2. Inspect the component.
3. Check the template.
4. Inspect the data being passed.
5. Check injected dependencies.
6. Check the browser console.
7. Check network requests.
8. Reduce the problem to a smaller example.
9. Consult `angular.dev`.
10. Search for the specific concept rather than copying an entire solution.

> **The objective is not to memorize Angular syntax. The objective is to understand how to design structured, maintainable and scalable web applications using Angular.**
