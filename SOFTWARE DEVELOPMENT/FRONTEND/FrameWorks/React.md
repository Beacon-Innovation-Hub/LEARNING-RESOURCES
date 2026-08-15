# ⚛️ React.js Learning Path

> Learn React by understanding components, building interactive interfaces, managing state, working with APIs, and developing real-world applications.

**Level:** 🟢 Beginner → 🔴 Advanced
**Prerequisite:** HTML, CSS & JavaScript
**Learning Model:** Watch → Read → Experiment → Practice → Build

---

## ⚠️ Before Starting React

React should not be your first introduction to JavaScript.

Before starting this learning path, you should be comfortable with:

* [ ] JavaScript variables
* [ ] Functions
* [ ] Arrow functions
* [ ] Arrays
* [ ] Objects
* [ ] `map()`
* [ ] `filter()`
* [ ] Destructuring
* [ ] Spread syntax
* [ ] ES modules
* [ ] DOM events
* [ ] Promises
* [ ] `async` / `await`
* [ ] `fetch()`
* [ ] APIs

If these concepts are unfamiliar, complete the relevant sections in `javascript.md` first.

---

# 📍 Learning Path

1. [React Foundations](#1-react-foundations)
2. [Components, Props, State & Forms](#2-components-props-state--forms)
3. [React Hooks](#3-react-hooks)
4. [APIs & Data Fetching](#4-apis--data-fetching)
5. [Routing & Application Structure](#5-routing--application-structure)
6. [Advanced State Management](#6-advanced-state-management)
7. [Professional React](#7-professional-react)
8. [Real-World React Projects](#8-real-world-react-projects)

---

# 1. React Foundations

**Level:** 🟢 Beginner

React applications are built from reusable components.

Begin by understanding how React differs from manually manipulating the DOM with JavaScript.

[![React Tutorial for Beginners](https://img.youtube.com/vi/SqcY0GlETPk/maxresdefault.jpg)](https://youtu.be/SqcY0GlETPk)

## 🎥 Primary Beginner Resource

**[▶ Watch: React Tutorial for Beginners](https://youtu.be/SqcY0GlETPk)**

---

## 🎥 Additional React Course

[![React Course](https://img.youtube.com/vi/V9i3cGD-mts/maxresdefault.jpg)](https://youtu.be/V9i3cGD-mts)

**[▶ Watch Additional React Course](https://youtu.be/V9i3cGD-mts)**

Use the second resource to reinforce concepts that remain unclear after completing the introductory tutorial.

You do not need to repeatedly watch material you already understand.

---

## 🎯 Learn

* What React is
* Why React is used
* React applications
* Components
* Functional components
* JSX
* JSX expressions
* Rendering components
* Nesting components
* Component composition
* Props
* Events
* State
* Conditional rendering
* Rendering lists
* Keys
* Basic project structure

---

# 📚 Official React Documentation

## React Quick Start

**[📘 React — Quick Start](https://react.dev/learn)**

Use the official documentation alongside the video resources.

Focus on:

* Creating components
* Nesting components
* JSX
* Displaying data
* Conditional rendering
* Rendering lists
* Responding to events
* Updating the screen
* Sharing data between components

---

## 🧪 Interactive React Learning

The official React documentation contains editable examples.

Use:

**[🚀 React Learn](https://react.dev/learn)**

Instead of only reading an example:

1. Run it.
2. Change the code.
3. Predict what will happen.
4. Break the example.
5. Fix it.
6. Add your own functionality.

---

# 🧩 Foundation Practice

Complete these before moving forward.

* [ ] Hello World component
* [ ] Profile component
* [ ] Navigation component
* [ ] Footer component
* [ ] Reusable Card component
* [ ] Product component
* [ ] User component
* [ ] Render a list of users
* [ ] Conditional login message
* [ ] Simple button event

---

## 🧩 Challenge — Developer Cards

Create:

```jsx
const developers = [
    {
        name: "Ayanda",
        role: "Frontend Developer",
        skills: ["HTML", "CSS", "JavaScript"]
    },
    {
        name: "Thando",
        role: "Backend Developer",
        skills: ["Python", "Django", "PostgreSQL"]
    }
];
```

Create a reusable:

```text
DeveloperCard
```

component.

Use props to display each developer.

Render all developers using:

```javascript
map()
```

Do not manually create a separate component call for every developer.

---

# 2. Components, Props, State & Forms

**Level:** 🟢 Beginner → 🟡 Intermediate

React becomes powerful when components communicate and respond to changing data.

---

# 🧩 Components & Props

[![React Components](https://img.youtube.com/vi/uvEAvxWvwOs/maxresdefault.jpg)](https://youtu.be/uvEAvxWvwOs)

## 🎥 Resource

**[▶ Watch: React Components & Props](https://youtu.be/uvEAvxWvwOs)**

---

## 🎯 Learn

* Component composition
* Parent components
* Child components
* Props
* Passing data
* Reusable components
* Rendering children
* Component responsibilities

---

## 🧪 Practice

* [ ] Build a `Profile` component
* [ ] Build a reusable `Card`
* [ ] Pass text through props
* [ ] Pass numbers through props
* [ ] Pass arrays through props
* [ ] Pass objects through props
* [ ] Render multiple cards from data

---

# 🔄 React State

[![React State](https://img.youtube.com/vi/4ORZ1GmjaMc/maxresdefault.jpg)](https://youtu.be/4ORZ1GmjaMc)

## 🎥 Resource

**[▶ Watch: React State](https://youtu.be/4ORZ1GmjaMc)**

---

## 📚 Official Documentation

**[📘 React — State: A Component's Memory](https://react.dev/learn/state-a-components-memory)**

**[📘 React — Adding Interactivity](https://react.dev/learn/adding-interactivity)**

---

## 🎯 Learn

* What state is
* `useState`
* Reading state
* Updating state
* State and rendering
* Events
* Event handlers
* Updating objects
* Updating arrays
* Conditional UI

---

## 🧩 State Practice

* [ ] Counter
* [ ] Like button
* [ ] Show/hide component
* [ ] Quantity selector
* [ ] Dark/light switch
* [ ] Expand/collapse section
* [ ] Image gallery

---

# 📝 React Forms

[![React Forms](https://img.youtube.com/vi/tIdNeoHniEY/maxresdefault.jpg)](https://youtu.be/tIdNeoHniEY)

## 🎥 Resource

**[▶ Watch: React Forms](https://youtu.be/tIdNeoHniEY)**

---

## 🎯 Learn

* Form components
* Inputs
* Handling input changes
* Form state
* Controlled inputs
* Form submission
* Validation
* Error messages
* Reusable form components

---

## 🧩 Form Practice

Build:

* [ ] Search form
* [ ] Login form
* [ ] Contact form
* [ ] Registration form

---

## 🧪 Registration Challenge

Create a registration form containing:

```text
Full Name
Email
Password
Confirm Password
Role
Terms & Conditions
Submit
```

Your application should:

* [ ] Store input values
* [ ] Validate required fields
* [ ] Validate email
* [ ] Check that passwords match
* [ ] Display validation errors
* [ ] Prevent invalid submission
* [ ] Display a success state

---

# 3. React Hooks

**Level:** 🟡 Intermediate

Hooks allow functional components to use React features such as state, context, refs and effects.

[![React Hooks](https://img.youtube.com/vi/xfKYYRE6-TQ/maxresdefault.jpg)](https://youtu.be/xfKYYRE6-TQ)

## 🎥 Resource

**[▶ Watch: React Hooks Explained](https://youtu.be/xfKYYRE6-TQ)**

---

# 📚 Official Hooks Documentation

**[📘 React — Built-in Hooks](https://react.dev/reference/react/hooks)**

---

## 🎯 Core Hooks

Study:

```text
useState
useEffect
useRef
useContext
useReducer
```

Then learn how custom Hooks can combine reusable logic.

---

# `useState`

Practice:

* [ ] Counter
* [ ] Toggle
* [ ] Form
* [ ] Shopping quantity selector
* [ ] Array state
* [ ] Object state

---

# `useEffect`

Learn when an Effect is actually necessary.

Use Effects primarily when synchronizing React with something outside React.

Examples include:

```text
Network connections
Browser APIs
Timers
External libraries
Subscriptions
```

Do not automatically use `useEffect` whenever state changes.

---

## 🧩 Effect Practice

Build:

* [ ] Document title updater
* [ ] Timer
* [ ] Window-size tracker
* [ ] Simple API loader

---

# `useRef`

Learn how refs can store information without triggering another render.

Practice:

* [ ] Focus an input
* [ ] Reference a DOM element
* [ ] Store a timer ID
* [ ] Track a previous value

---

# `useContext`

Use Context when information needs to be available deeper in the component tree.

Practice:

* [ ] Theme context
* [ ] User context
* [ ] Language preference

---

# `useReducer`

Use reducers when state-update logic becomes more complex.

Practice by rebuilding your To-Do application using:

```javascript
useReducer()
```

instead of multiple state-update functions.

---

# 🪝 Custom Hooks

Create reusable hooks such as:

```text
useLocalStorage()
useWindowSize()
useFetch()
```

Understand why the reusable logic belongs in a custom Hook.

---

# 4. APIs & Data Fetching

**Level:** 🟡 Intermediate

React applications frequently consume data from APIs.

---

## 🎥 Learning Resources

[![React API Resource](https://img.youtube.com/vi/je3FTTunyp4/maxresdefault.jpg)](https://youtu.be/je3FTTunyp4)

**[▶ Watch API Resource](https://youtu.be/je3FTTunyp4)**

[![React Data Resource](https://img.youtube.com/vi/00lxm_doFYw/maxresdefault.jpg)](https://youtu.be/00lxm_doFYw)

**[▶ Watch Data Resource](https://youtu.be/00lxm_doFYw)**

---

## 🎯 Learn

* API requests
* `fetch()`
* `async` / `await`
* JSON
* Data state
* Loading state
* Error state
* Empty state
* Rendering API data
* Search
* Filtering
* Refreshing data
* Separating API logic from UI logic

---

# 🧩 API Practice

## Project 1 — User Directory

Fetch users from an API.

Display:

```text
Name
Username
Email
Company
```

Implement:

* [ ] Loading state
* [ ] Success state
* [ ] Error state
* [ ] Search

---

## Project 2 — GitHub Profile Viewer

Allow users to search for a GitHub username.

Display:

* [ ] Avatar
* [ ] Username
* [ ] Biography
* [ ] Followers
* [ ] Following
* [ ] Repository count

Handle:

* [ ] Loading
* [ ] User not found
* [ ] Network error

---

## Project 3 — Weather Interface

Build a weather application.

The application should support:

```text
Search city
     ↓
Request data
     ↓
Loading state
     ↓
Weather result
```

Also handle:

```text
Invalid city
API failure
Network failure
```

---

# 5. Routing & Application Structure

**Level:** 🟡 Intermediate

Larger applications require navigation between different views.

[![React Routing](https://img.youtube.com/vi/ehvS1Hp90KU/maxresdefault.jpg)](https://youtu.be/ehvS1Hp90KU)

## 🎥 Resource

**[▶ Watch React Routing Resource](https://youtu.be/ehvS1Hp90KU)**

---

# 📚 React Router

**[📘 React Router Documentation](https://reactrouter.com/)**

---

## 🎯 Learn

* Client-side routing
* Routes
* Links
* Navigation
* Route parameters
* Nested routes
* Layouts
* URL parameters
* Not-found pages
* Programmatic navigation
* Protected-route concepts

---

# 🧩 Routing Exercise

Create:

```text
/
├── Home
├── About
├── Projects
│   └── /projects/:id
├── Contact
└── 404
```

Build navigation between these views without traditional full-page reloads.

---

# 🏗️ Application Structure

As projects become larger, avoid putting everything inside:

```text
App.jsx
```

A project might instead become:

```text
src/
│
├── components/
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   └── Card.jsx
│
├── pages/
│   ├── Home.jsx
│   ├── About.jsx
│   ├── Projects.jsx
│   └── Contact.jsx
│
├── hooks/
│   └── useFetch.js
│
├── services/
│   └── api.js
│
├── context/
│   └── AppContext.jsx
│
├── App.jsx
└── main.jsx
```

Do not copy this structure mechanically.

The structure should reflect the requirements of the application.

---

# 6. Advanced State Management

**Level:** 🔴 Advanced

As applications grow, state relationships become more complicated.

[![React State Management](https://img.youtube.com/vi/-bEzt5ISACA/maxresdefault.jpg)](https://youtu.be/-bEzt5ISACA)

## 🎥 Resource

**[▶ Watch React State Management](https://youtu.be/-bEzt5ISACA)**

---

# 📚 Required Documentation

**[📘 React — Managing State](https://react.dev/learn/managing-state)**

**[📘 React — Reducer + Context](https://react.dev/learn/scaling-up-with-reducer-and-context)**

---

## 🎯 Learn

* Local state
* Shared state
* State ownership
* Lifting state
* Avoiding redundant state
* Avoiding duplicated state
* Derived state
* Context
* Reducers
* Reducer + Context
* State architecture

---

# 🧩 Shopping Cart Challenge

Build a shopping cart.

Users should be able to:

* [ ] Add products
* [ ] Remove products
* [ ] Increase quantity
* [ ] Decrease quantity
* [ ] View total items
* [ ] View total price
* [ ] Clear the cart

Before coding, decide:

```text
Which component owns the products?

Which component owns the cart?

Which values are state?

Which values can be calculated?

Which components need access to the state?
```

---

# 🧩 Refactoring Challenge

Take an earlier React application.

Identify:

* [ ] Duplicate state
* [ ] Unnecessary state
* [ ] Derived values stored as state
* [ ] State that should remain local
* [ ] State that should move upward
* [ ] Excessive prop drilling

Refactor the application.

---

# 7. Professional React

**Level:** 🔴 Advanced

The objective now changes from:

> **Does the application work?**

to:

> **Is the application maintainable, testable, accessible, secure and understandable?**

---

## 🎥 Professional React Resource

[![Professional React](https://img.youtube.com/vi/8Xwq35cPwYg/maxresdefault.jpg)](https://youtu.be/8Xwq35cPwYg)

**[▶ Watch Professional React Resource](https://youtu.be/8Xwq35cPwYg)**

---

# 🧪 React Testing

[![React Testing](https://img.youtube.com/vi/JBSUgDxICg8/maxresdefault.jpg)](https://youtu.be/JBSUgDxICg8)

**[▶ Watch React Testing Tutorial](https://youtu.be/JBSUgDxICg8)**

---

## 🎯 Learn Testing

Understand:

* Component testing
* Assertions
* Rendering components
* Querying elements
* User interactions
* Form testing
* Async testing
* Mocking
* Error-state testing

---

## 📚 Testing Library

**[📘 React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)**

---

## 🧩 Testing Practice

Write tests for:

* [ ] Button
* [ ] Counter
* [ ] Form
* [ ] Form validation
* [ ] To-do item
* [ ] Search interface
* [ ] API loading state
* [ ] API success state
* [ ] API error state

Focus tests on **what the user can observe and do**, rather than internal implementation details.

---

# ♿ Accessibility

Professional React applications still produce HTML.

Everything learned in `html.md` about accessibility remains relevant.

Review:

* [ ] Semantic HTML
* [ ] Labels
* [ ] Alternative text
* [ ] Keyboard navigation
* [ ] Focus states
* [ ] Accessible forms
* [ ] Buttons vs clickable `<div>` elements
* [ ] Heading hierarchy
* [ ] ARIA only when appropriate

---

# 🐛 Debugging

Learn to debug React using:

* Browser Developer Tools
* React Developer Tools
* Console
* Network panel
* Breakpoints
* Component inspection

Do not rely exclusively on:

```javascript
console.log()
```

---

# ⚡ Performance

Understand:

* Why components render
* Avoiding unnecessary state
* Component boundaries
* Expensive calculations
* Lazy loading concepts
* Code splitting concepts
* Profiling

Do not optimize everything prematurely.

Measure first.

---

# 🔐 Security

Understand frontend security fundamentals:

* [ ] Never trust user input
* [ ] Avoid unsafe HTML injection
* [ ] Understand XSS
* [ ] Do not expose secrets in frontend code
* [ ] Understand API-key exposure
* [ ] Validate data
* [ ] Keep dependencies updated
* [ ] Understand third-party package risk

---

# 8. Real-World React Projects

**Level:** 🟡 Intermediate → 🔴 Advanced

At this stage, reduce your dependence on tutorials.

You should increasingly build from:

```text
Requirements
Design
Problem statement
API documentation
```

rather than copying finished code.

---

# 🏗️ Interactive Project Platform

## Frontend Mentor

**[🚀 React & Frontend Challenges](https://www.frontendmentor.io/)**

Choose increasingly difficult projects.

---

# 🟢 Project 1 — Interactive Rating Component

Build:

```text
Rating selection
      ↓
Submit
      ↓
Thank-you state
```

Practice:

* Components
* Props
* State
* Events
* Conditional rendering

---

# 🟢 Project 2 — FAQ Application

Create reusable:

```text
FAQ
FAQItem
```

components.

Users should be able to expand and collapse questions.

---

# 🟡 Project 3 — Expense Tracker

Users should be able to:

* [ ] Add transactions
* [ ] Delete transactions
* [ ] Categorize expenses
* [ ] Calculate total expenses
* [ ] Calculate total income
* [ ] Calculate balance
* [ ] Filter transactions

---

# 🟡 Project 4 — To-Do Application

Implement:

* [ ] Create task
* [ ] Edit task
* [ ] Delete task
* [ ] Complete task
* [ ] Filter tasks
* [ ] Persist tasks
* [ ] Multiple components

---

# 🟡 Project 5 — API Application

Build an application containing:

```text
Search
Filtering
API requests
Loading state
Error state
Empty state
Results
```

Possible applications:

* Country explorer
* Weather application
* Movie search
* GitHub profile explorer
* Public-data dashboard

---

# 🔴 Project 6 — E-Commerce Frontend

Build:

```text
Products
Product details
Search
Filtering
Categories
Cart
Quantity
Totals
Checkout interface
Routing
```

Use appropriate state-management techniques.

---

# 🔴 Project 7 — Dashboard

Build a dashboard containing:

* [ ] Multiple pages
* [ ] Routing
* [ ] API integration
* [ ] Search
* [ ] Filtering
* [ ] Sorting
* [ ] Forms
* [ ] Loading states
* [ ] Error states
* [ ] Shared state
* [ ] Reusable components
* [ ] Responsive interface

---

# 🔴 Project 8 — Full React Application

Create a larger application from an unfamiliar specification.

A possible structure:

```text
src/
│
├── components/
├── pages/
├── layouts/
├── hooks/
├── context/
├── services/
├── utils/
├── assets/
│
├── App.jsx
└── main.jsx
```

The application should combine concepts from the entire learning path.

---

# 🎮 Interactive React Learning

Use these throughout the course.

## ⚛️ React Documentation

**[🚀 React Learn](https://react.dev/learn)**

The official documentation contains editable examples and challenges.

---

## 🧪 CodeSandbox

**[🚀 CodeSandbox](https://codesandbox.io/)**

Useful for quickly experimenting with React applications without creating a full local project.

---

## 🧪 StackBlitz

**[🚀 StackBlitz](https://stackblitz.com/)**

Useful for running and experimenting with React projects directly in the browser.

---

## 🏗️ Frontend Mentor

**[🚀 Frontend Mentor](https://www.frontendmentor.io/)**

Use design briefs to practise building interfaces without copying tutorial code.

---

# 📊 Progress Checklist

Use this as a quick overview of your progress.

## 🟢 Level 1 — React Foundations

* [ ] Beginner React tutorial
* [ ] React Quick Start
* [ ] Components
* [ ] JSX
* [ ] Props
* [ ] Events
* [ ] Lists
* [ ] Conditional rendering
* [ ] Foundation exercises

## 🟢 Level 2 — Components, State & Forms

* [ ] Components & props
* [ ] `useState`
* [ ] Events
* [ ] Updating state
* [ ] Forms
* [ ] Form validation
* [ ] Registration challenge

## 🟡 Level 3 — Hooks

* [ ] `useState`
* [ ] `useEffect`
* [ ] `useRef`
* [ ] `useContext`
* [ ] `useReducer`
* [ ] Custom Hooks
* [ ] Hook exercises

## 🟡 Level 4 — APIs

* [ ] Fetching data
* [ ] Loading states
* [ ] Error states
* [ ] Empty states
* [ ] API project

## 🟡 Level 5 — Routing

* [ ] React Router
* [ ] Routes
* [ ] Links
* [ ] Parameters
* [ ] Nested layouts
* [ ] 404 page
* [ ] Multi-page-style application

## 🔴 Level 6 — State Management

* [ ] State ownership
* [ ] Lifting state
* [ ] Context
* [ ] Reducers
* [ ] Reducer + Context
* [ ] Shopping-cart challenge

## 🔴 Level 7 — Professional React

* [ ] Project organization
* [ ] Testing
* [ ] Accessibility
* [ ] Debugging
* [ ] Performance fundamentals
* [ ] Security fundamentals

## 🏗️ Projects

* [ ] Rating component
* [ ] FAQ
* [ ] Expense tracker
* [ ] To-do application
* [ ] API application
* [ ] E-commerce frontend
* [ ] Dashboard
* [ ] Larger React application

---

# 🚀 Complete React Progression

```text
JavaScript Fundamentals
          ↓
🟢 React Foundations
          ↓
🟢 Components, Props, State & Forms
          ↓
🟡 React Hooks
          ↓
🟡 APIs & Data Fetching
          ↓
🟡 Routing & Application Structure
          ↓
🔴 Advanced State Management
          ↓
🔴 Professional React
          ↓
🏗️ Real-World React Applications
```

---

# 💡 Learning Principle

React should be learned by **building interfaces**, not by watching tutorials continuously.

Follow this cycle:

```text
🎥 Watch
    ↓
📚 Read Official Documentation
    ↓
🧪 Experiment
    ↓
🧩 Solve a Small Problem
    ↓
💻 Build
    ↓
🐛 Debug
    ↓
🔁 Refactor
```

When stuck:

1. Read the error message.
2. Inspect the component.
3. Inspect the current state.
4. Check the props.
5. Reduce the problem to a smaller example.
6. Consult the React documentation.
7. Use React Developer Tools.
8. Search for the specific concept rather than copying an entire solution.

> **The objective is not to memorize React. The objective is to understand how to design a user interface as components, state, data flow, and user interactions.**
