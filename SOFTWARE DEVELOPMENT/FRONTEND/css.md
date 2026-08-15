# 🎨 CSS Learning Path

> Learn CSS by watching, reading, experimenting, and building real-world projects.

**Level:** 🟢 Beginner → 🔴 Advanced
**Prerequisite:** Basic HTML knowledge
**Learning Model:** Watch → Read → Practice → Build

---

## 📍 Learning Path

1. [CSS Foundations](#1-css-foundations)
2. [Practice CSS Live](#2-practice-css-live)
3. [Practice Problems](#3-practice-problems)
4. [Real-World CSS Projects](#4-real-world-css-projects)
5. [Browser Developer Tools](#5-browser-developer-tools)
6. [Next Learning Stage](#6-next-learning-stage)

---

# 1. CSS Foundations

**Level:** 🟢 Beginner

[![CSS Tutorial for Beginners](https://img.youtube.com/vi/wRNinF7YQqQ/maxresdefault.jpg)](https://youtu.be/wRNinF7YQqQ)

## 🎯 Learning Objectives

Develop an understanding of:

* What CSS is
* CSS syntax
* Selectors
* Properties and values
* External, internal and inline CSS
* Colors and backgrounds
* Typography
* Width and height
* Borders
* Margin and padding
* The CSS Box Model
* Classes and IDs
* Hover states
* Cascade
* Inheritance
* Specificity

---

## 🎥 Beginner Video

**[▶ Watch: CSS Tutorial for Beginners](https://youtu.be/wRNinF7YQqQ)**

Use this tutorial to establish your CSS foundation before moving into documentation and practical work.

---

## 📚 Conceptual Understanding

Videos provide an introduction. Technical documentation should be used to understand CSS concepts in greater depth and as a reference during development.

### 📘 MDN — CSS Styling Basics

**[Read CSS Styling Basics →](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics)**

Focus on:

* CSS rules
* Selectors
* Properties and values
* The Box Model
* Cascade
* Specificity
* Inheritance
* CSS values and units

### 📘 MDN — Getting Started with CSS

**[Read Getting Started with CSS →](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Getting_started)**

Use this guide to understand how CSS connects to HTML and how browsers apply styles.

### 📘 MDN — CSS Reference

**[Open CSS Reference →](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)**

Use the CSS Reference whenever you encounter an unfamiliar:

* Property
* Selector
* Function
* Value
* Pseudo-class
* Pseudo-element

---

# 2. Practice CSS Live

Do not only read CSS.

Write CSS, change values, break the design, fix it, and observe how the browser responds.

## 🟢 MDN Playground

**[🚀 Practice with MDN Playground →](https://developer.mozilla.org/en-US/play)**

Use MDN Playground to experiment with HTML and CSS directly in your browser and immediately see the output.

## 🔵 CodePen

**[🚀 Practice with CodePen →](https://codepen.io/pen/)**

CodePen provides HTML and CSS editors alongside a live preview.

---

## 🔬 Quick Experiment

Add this HTML to your chosen playground:

```html
<div class="card">
    <h1>My First CSS Card</h1>

    <p>
        I am learning how CSS changes the appearance of HTML.
    </p>

    <button>Learn More</button>
</div>
```

Add the following CSS:

```css
.card {
    width: 300px;
    padding: 30px;
    margin: 40px auto;
    border: 1px solid #ccc;
    border-radius: 12px;
    text-align: center;
}

.card h1 {
    font-size: 24px;
}

.card button {
    padding: 10px 20px;
    cursor: pointer;
}

.card button:hover {
    transform: scale(1.05);
}
```

### 🔧 Experiment

Change these properties one at a time:

* `width`
* `padding`
* `margin`
* `font-size`
* `border`
* `border-radius`
* `text-align`

Observe what happens after every change.

---

# 3. Practice Problems

Practice problems should be attempted independently before looking for solutions.

---

## 🟢 Problem 1 — Style a Basic Webpage

Create:

```text
practice-01/
├── index.html
└── style.css
```

Your page should contain:

* Heading
* Subheading
* Three paragraphs
* Image
* Link
* Button

Use CSS to change:

* Typography
* Font sizes
* Background
* Spacing
* Borders
* Button appearance

---

## 🟢 Problem 2 — Profile Card

Create a profile card containing:

* Profile image
* Name
* Short biography
* Skills
* Contact button

Use CSS to implement:

* Width
* Padding
* Margin
* Border
* Border radius
* Text alignment
* Hover effect

Try to centre the card on the page.

---

## 🟢 Problem 3 — Navigation Bar

Create a navigation bar containing:

```text
Home
About
Projects
Contact
```

Style the navigation so that:

* Default link underlines are removed
* Links have appropriate spacing
* Links visually change when hovered
* The navigation is visually separated from the page content

---

## 🟢 Problem 4 — Product Card

Create a product card containing:

* Product image
* Product name
* Description
* Price
* "Buy Now" button

Experiment with:

* Box Model
* Shadows
* Borders
* Spacing
* Typography
* Button states

---

## 🟡 Problem 5 — Login Form

Build a styled login interface containing:

* Email field
* Password field
* Remember me option
* Login button
* Forgot password link

Focus on:

* Form spacing
* Input sizing
* Labels
* Borders
* Focus states
* Button hover states

---

## 🟡 Problem 6 — Landing Page

Build a landing page containing:

* Header
* Navigation
* Hero section
* Main heading
* Supporting text
* Call-to-action button
* Features section
* Footer

Do not copy an existing CSS template.

Create your own layout and visual hierarchy.

---

## 🟡 Problem 7 — Recreate a Design

Find a simple webpage or interface that you like.

Without copying its source code:

1. Study its layout.
2. Identify the major sections.
3. Recreate the HTML structure.
4. Reproduce the appearance using your own CSS.
5. Compare your result with the original.
6. Identify what you would improve.

---

# 4. Real-World CSS Projects

Once you understand the fundamentals, start applying CSS to complete interfaces.

## 🏗️ Real-World Project Playlist

**[▶ Open the Real-World Projects Playlist](https://www.youtube.com/playlist?list=PLRjB3Wml-DM_VWMDomFed97f74dpCO7GE)**

Use the playlist to observe how CSS concepts are combined when building complete projects.

### Recommended Approach

Do **not** simply code along from beginning to end.

For each project:

1. Watch the introduction and understand the intended design.
2. Pause the video.
3. Attempt to build the interface yourself.
4. Use MDN when you encounter unfamiliar CSS.
5. Compare your implementation with the tutorial.
6. Identify differences.
7. Refactor your CSS.
8. Complete the project independently.

### 📁 Store Each Project Separately

```text
css-projects/
│
├── project-01/
│   ├── index.html
│   └── style.css
│
├── project-02/
│   ├── index.html
│   └── style.css
│
└── project-03/
    ├── index.html
    └── style.css
```

---

# 5. Browser Developer Tools

Learning CSS also means learning how to debug it.

Open one of your webpages in a browser and use **Developer Tools → Inspect**.

Practice:

1. Selecting HTML elements.
2. Viewing applied CSS.
3. Enabling and disabling properties.
4. Editing CSS values.
5. Inspecting margin and padding.
6. Inspecting the Box Model.
7. Identifying inherited styles.
8. Identifying overridden styles.
9. Investigating specificity.
10. Testing changes before editing your stylesheet.

Developer Tools changes are temporary, making them ideal for experimentation.

---

# 6. Next Learning Stage

After CSS foundations, continue developing your skills in modern layout and responsive design.

## 🟡 Flexbox

Study:

* `display: flex`
* Flex containers and items
* Main and cross axes
* `flex-direction`
* `justify-content`
* `align-items`
* `gap`
* `flex-wrap`
* `flex-grow`
* `flex-shrink`

### 🎮 Practice

**[Flexbox Froggy →](https://flexboxfroggy.com/)**

---

## 🟡 CSS Grid

Study:

* `display: grid`
* Grid containers
* Rows and columns
* Grid tracks
* `grid-template-columns`
* `grid-template-rows`
* `gap`
* Grid placement
* Responsive grids

### 🎮 Practice

**[Grid Garden →](https://cssgridgarden.com/)**

---

## 🟡 Responsive Web Design

Study:

* Mobile-first design
* Media queries
* Relative units
* `%`
* `rem`
* `em`
* `vw`
* `vh`
* `min()`
* `max()`
* `clamp()`
* Responsive images
* Flexible layouts

---

## 🚀 Learning Progression

```text
🟢 CSS Foundations
        ↓
🧪 Practice Problems
        ↓
🏗️ Real-World Projects
        ↓
🟡 Flexbox
        ↓
🟡 CSS Grid
        ↓
🟡 Responsive Web Design
        ↓
🔴 Advanced & Professional CSS
```

---

> **Learning Principle:** Do not try to memorize every CSS property. Learn how to use documentation, experiment with CSS, inspect the result, identify problems, debug them, and improve your implementation.
