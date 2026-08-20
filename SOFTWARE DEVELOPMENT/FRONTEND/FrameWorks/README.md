
# Frontend Development Frameworks

> Structured learning resources for developing competence in modern frontend frameworks used to build interactive, scalable, and maintainable web applications.

**Department:** Software Development
**Area:** Frontend Development
**Prerequisite:** HTML, CSS, and JavaScript fundamentals
**Learning Model:** Learn → Practice → Build → Compare → Demonstrate Competence

---

## Overview

Modern frontend development extends beyond HTML, CSS, and JavaScript fundamentals.

Frontend frameworks and libraries provide structured approaches for developing larger applications through concepts such as:

* Component-based architecture
* Reusable user interfaces
* State management
* Routing
* Event handling
* Data binding
* API integration
* Application architecture
* Build tools
* Testing
* Performance optimization

This directory provides separate learning pathways for major frontend technologies.

---

## Available Learning Paths

| Technology | Type      | Learning Path                       |
| ---------- | --------- | ----------------------------------- |
| Angular    | Framework | [Angular Learning Path](Angular.md) |
| React      | Library   | [React Learning Path](React.md)     |
| Svelte     | Framework | [Svelte Learning Path](Svelte.md)   |
| Vue        | Framework | [Vue Learning Path](Vue.md)         |

---

# Prerequisites

Before beginning a frontend framework, participants should have a working understanding of:

## HTML

* [ ] Semantic HTML
* [ ] Forms
* [ ] Tables
* [ ] Links and navigation
* [ ] Images and media
* [ ] Accessibility fundamentals

## CSS

* [ ] Selectors
* [ ] Box Model
* [ ] Flexbox
* [ ] CSS Grid
* [ ] Responsive design
* [ ] Media queries
* [ ] Component styling
* [ ] Browser Developer Tools

## JavaScript

* [ ] Variables and data types
* [ ] Functions
* [ ] Arrays and objects
* [ ] Loops
* [ ] DOM manipulation
* [ ] Events
* [ ] Modules
* [ ] Destructuring
* [ ] Spread syntax
* [ ] Promises
* [ ] `async` / `await`
* [ ] Fetch API
* [ ] Error handling

> Participants who cannot comfortably build a small interactive website using HTML, CSS, and JavaScript should complete the frontend foundations before specializing in a framework.

---

# Learning Progression

```text
HTML
  ↓
CSS
  ↓
JavaScript
  ↓
Frontend Foundations
  ↓
Choose a Framework / Library
  ↓
┌─────────┬─────────┬─────────┬─────────┐
│ Angular │  React  │ Svelte  │   Vue   │
└─────────┴─────────┴─────────┴─────────┘
  ↓
Component-Based Development
  ↓
Routing & State Management
  ↓
API Integration
  ↓
Testing & Debugging
  ↓
Real-World Projects
  ↓
Competence Assessment
  ↓
Technical Defence
  ↓
Junior Frontend Developer Readiness
```

---

# Choosing a Learning Path

Participants are **not required to learn every framework before becoming competent frontend developers**.

Choose one primary technology and develop sufficient depth to build complete applications independently.

## React

Choose the [React Learning Path](React.md) to study component-based development using one of the most widely adopted JavaScript UI libraries.

Focus on:

* Components
* JSX
* Props
* State
* Hooks
* Forms
* Routing
* API integration
* Reusable UI architecture

---

## Angular

Choose the [Angular Learning Path](Angular.md) for a more structured application framework.

Focus on:

* TypeScript
* Components
* Templates
* Services
* Dependency injection
* Routing
* Forms
* HTTP communication
* Application architecture

---

## Vue

Choose the [Vue Learning Path](Vue.md) to learn progressive component-based frontend development.

Focus on:

* Vue components
* Templates
* Directives
* Props
* Events
* Reactivity
* Composition API
* Routing
* State management

---

## Svelte

Choose the [Svelte Learning Path](Svelte.md) to explore a compiler-based approach to frontend application development.

Focus on:

* Components
* Reactivity
* Props
* Events
* Bindings
* Stores
* Routing
* Application development

---

# Framework Learning Standard

Regardless of the selected technology, participants should develop competence in the following areas.

| Competence     | Expected Ability                        |
| -------------- | --------------------------------------- |
| Components     | Build reusable UI components            |
| State          | Manage changing application data        |
| Props / Inputs | Transfer information between components |
| Events         | Respond to user interactions            |
| Forms          | Build and validate user input           |
| Routing        | Create multi-view applications          |
| APIs           | Retrieve and submit external data       |
| Error Handling | Handle failed operations appropriately  |
| Styling        | Build responsive interfaces             |
| Architecture   | Organize applications logically         |
| Debugging      | Diagnose application problems           |
| Git            | Maintain professional version control   |
| Documentation  | Explain setup, structure and decisions  |

---

# Practical Development Approach

Do not learn frameworks by watching tutorials alone.

Use the following workflow:

```text
Learn Concept
      ↓
Read Documentation
      ↓
Build Small Example
      ↓
Modify Example
      ↓
Break It
      ↓
Debug It
      ↓
Build Without Tutorial
      ↓
Apply to Project
      ↓
Review & Refactor
```

When following a project tutorial:

1. Understand the project requirements.
2. Watch only enough to understand the intended result.
3. Stop the tutorial.
4. Attempt the implementation independently.
5. Consult official documentation when blocked.
6. Return to the tutorial only when necessary.
7. Compare implementations.
8. Refactor your solution.
9. Document what you learned.

---

# BIH Project Standard

Framework projects should demonstrate more than visual design.

A project should contain:

```text
Problem
   ↓
Requirements
   ↓
UI Architecture
   ↓
Components
   ↓
State
   ↓
Routing
   ↓
API / Data
   ↓
Error Handling
   ↓
Responsive Design
   ↓
Testing
   ↓
Documentation
```

---

# Recommended Repository Structure

Each major framework project should have its own repository or clearly separated project directory.

```text
frontend-project/
│
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── styles/
│   └── ...
│
├── tests/
├── .gitignore
├── package.json
└── README.md
```

Exact structures will differ between Angular, React, Svelte, and Vue.

Follow the conventions of the selected technology rather than forcing every framework into the same architecture.

---

# Competence Assessment

Completion of videos does not demonstrate framework competence.

Participants should be assessed through practical implementation.

A competence assessment should require the participant to:

* Build an application from requirements
* Create reusable components
* Implement responsive interfaces
* Manage application state
* Implement routing
* Consume an API
* Handle loading and error states
* Validate user input
* Debug supplied problems
* Use Git appropriately
* Document the application
* Explain technical decisions

---

# Technical Defence

After completing a competence project, the participant should be able to explain their implementation.

Example questions include:

1. Why did you choose this component structure?
2. Which component owns this state and why?
3. How does data move through the application?
4. What happens when the API request fails?
5. Why did you create this component instead of writing the UI directly on the page?
6. How does routing work in your application?
7. How is form input validated?
8. What would happen if the application became significantly larger?
9. How would you improve performance?
10. What would you refactor?
11. Which framework feature solved this problem?
12. Could the same problem have been solved using plain JavaScript?

The participant should demonstrate understanding rather than memorized terminology.

---

# Framework vs Fundamentals

Framework knowledge should never replace JavaScript knowledge.

```text
Strong Fundamentals
        +
Framework Competence
        +
Problem Solving
        +
Software Engineering
        =
Professional Frontend Development
```

Frameworks change.

The underlying principles of:

* HTML
* CSS
* JavaScript
* HTTP
* APIs
* accessibility
* browser behaviour
* software architecture
* testing
* debugging

remain essential.

---

# Progress Tracker

## Foundation

* [ ] HTML competence
* [ ] CSS competence
* [ ] JavaScript competence
* [ ] Git fundamentals
* [ ] Browser Developer Tools

## Framework

* [ ] Framework fundamentals
* [ ] Components
* [ ] Props / inputs
* [ ] State
* [ ] Events
* [ ] Forms
* [ ] Routing
* [ ] API integration
* [ ] Error handling
* [ ] Styling
* [ ] Application architecture

## Professional Development

* [ ] Responsive application
* [ ] Accessibility
* [ ] Testing
* [ ] Debugging
* [ ] Performance awareness
* [ ] Git workflow
* [ ] Documentation
* [ ] Independent project

## Competence

* [ ] Framework competence project
* [ ] Code review
* [ ] Technical defence
* [ ] Required assessment standard achieved

---

# Completion Standard

A participant completing a frontend framework pathway should be able to receive an unfamiliar application requirement and independently:

```text
Understand Requirements
        ↓
Plan Components
        ↓
Build Interface
        ↓
Manage State
        ↓
Connect Data
        ↓
Handle User Interaction
        ↓
Validate
        ↓
Test
        ↓
Debug
        ↓
Refactor
        ↓
Document
        ↓
Defend Technical Decisions
```

> **The objective is not to know the greatest number of frontend frameworks. The objective is to understand frontend development deeply enough to use the appropriate tools to build reliable, maintainable applications.**

---

## Continue Learning

Select your primary framework:

* **[Angular →](Angular.md)**
* **[React →](React.md)**
* **[Svelte →](Svelte.md)**
* **[Vue →](Vue.md)**

---

**Beacon Innovation Hub — Learning Resources**
*Developing practical competence through structured learning, projects, assessment and technical defence.*
