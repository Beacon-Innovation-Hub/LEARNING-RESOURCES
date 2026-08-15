# 🎨 CSS Learning Path

> Learn CSS by watching, reading, experimenting, building, and reviewing your own work.

**Level:** 🟢 Beginner → 🔴 Advanced
**Prerequisite:** Basic HTML knowledge
**Learning Model:** Watch → Read → Practice → Build → Review

---

## 📍 Learning Path

1. [CSS Foundations](#1-css-foundations)
2. [Practice CSS Live](#2-practice-css-live)
3. [Beginner Practice](#3-beginner-practice)
4. [Beginner Project](#4-beginner-project)
5. [Browser Developer Tools](#5-browser-developer-tools)
6. [Competence Standard](#6-competence-standard)
7. [Next Learning Stage](#7-next-learning-stage)

---

# 1. CSS Foundations

**Level:** 🟢 Beginner

[![CSS Tutorial for Beginners](https://img.youtube.com/vi/wRNinF7YQqQ/maxresdefault.jpg)](https://youtu.be/wRNinF7YQqQ)

### 🎯 Learning Objectives

By the end of this section, you should understand:

* What CSS is
* The role of CSS in web development
* CSS syntax
* Selectors
* Properties and values
* External CSS
* Internal CSS
* Inline CSS
* Colors
* Backgrounds
* Typography
* Width and height
* Borders
* Margin
* Padding
* The CSS Box Model
* Classes
* IDs
* Hover states
* Cascade
* Inheritance
* Specificity

---

## 🎥 Video Resource

### CSS Tutorial for Beginners

**[▶ Watch the CSS Tutorial on YouTube](https://youtu.be/wRNinF7YQqQ)**

Use this tutorial as your introduction to CSS before moving into documentation and practical work.

---

## 📚 Conceptual Understanding

Watching tutorials is only the first step.

Use technical documentation to understand how CSS works and to develop the habit of consulting professional developer references.

### 📘 MDN — CSS Styling Basics

**[Read CSS Styling Basics →](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics)**

Use this resource to strengthen your understanding of:

* CSS rules
* Selectors
* Properties
* Values
* Cascade
* Specificity
* Inheritance
* Box Model
* CSS values and units

### 📘 MDN — Getting Started with CSS

**[Read Getting Started with CSS →](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Getting_started)**

Use this guide to understand how CSS is connected to HTML and how browsers apply styles.

### 📘 MDN — CSS Reference

**[Open the CSS Reference →](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)**

Use the CSS Reference whenever you encounter an unfamiliar:

* CSS property
* Selector
* Function
* Value
* Pseudo-class
* Pseudo-element

---

# 2. Practice CSS Live

CSS should not only be read.

You should regularly change CSS values and observe how those changes affect the webpage.

---

## 🟢 MDN Playground

**[🚀 Open MDN Playground →](https://developer.mozilla.org/en-US/play)**

MDN Playground allows you to experiment with HTML and CSS directly in your browser and immediately see the output.

---

## 🔵 CodePen

**[🚀 Open CodePen →](https://codepen.io/pen/)**

CodePen provides separate HTML and CSS editors with a live webpage preview.

Use these tools when you want to test a CSS concept without creating an entire project.

---

## 🔬 CSS Experiment

Copy the following HTML into your chosen playground.

```html
<div class="card">
    <h1>My First CSS Card</h1>

    <p>
        I am learning how CSS changes the appearance of HTML.
    </p>

    <button>Learn More</button>
</div>
```

Add the following CSS.

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

### 🔧 Experiment With the Code

Change the following values one at a time:

* `width`
* `padding`
* `margin`
* `font-size`
* `border-radius`
* `text-align`
* `border`

Observe what happens after each change.

Do not simply copy the code.

Try to understand **why the output changes**.

---

# 3. Beginner Practice

Create the following files:

```text
index.html
css/
└── style.css
```

Connect the external CSS file to your HTML document.

Example:

```html
<link rel="stylesheet" href="css/style.css">
```

Your webpage should demonstrate the use of:

* Element selectors
* Class selectors
* ID selectors
* Text styling
* Font sizes
* Backgrounds
* Borders
* Margin
* Padding
* Width
* Height
* Hover states
* Basic CSS Box Model understanding

---

## 🧪 Practice Challenge

Create three cards on a webpage.

Each card should contain:

* A heading
* A paragraph
* A button

Use CSS to make the cards visually consistent.

You should experiment with:

```css
width
padding
margin
border
border-radius
font-size
text-align
background
```

Then modify the design using Browser Developer Tools before updating your stylesheet.

---

# 4. Beginner Project

## 💻 Build a Personal Profile Page

Create a professional personal profile webpage using HTML and CSS.

The objective is to demonstrate that you can style an HTML document independently.

---

## Required Sections

Your page should contain:

* Header
* Navigation
* Profile section
* About section
* Skills section
* Contact section
* Footer

---

## CSS Requirements

Your project should demonstrate:

* Typography
* Colors
* Backgrounds
* Borders
* Margin
* Padding
* Classes
* Appropriate selectors
* Hover effects
* Visual hierarchy
* Consistent spacing
* Basic layout principles

---

## Suggested Project Structure

```text
css-beginner-project/
│
├── index.html
│
├── css/
│   └── style.css
│
├── images/
│
└── README.md
```

---

## 🚫 Avoid

Do not:

* Copy an entire website template
* Copy CSS without understanding it
* Use excessive inline CSS
* Use random values without understanding their effect
* Use `!important` to solve every styling problem

The objective is to demonstrate your understanding of CSS.

---

# 5. Browser Developer Tools

Professional developers regularly inspect and debug CSS using browser Developer Tools.

You should become comfortable using them early.

---

## 🛠️ Practice

Open your webpage in your browser.

Right-click an element and select:

**Inspect**

Use Developer Tools to:

1. Inspect HTML elements.
2. View the CSS rules applied to an element.
3. Enable and disable CSS properties.
4. Edit property values.
5. Test different units.
6. Inspect the CSS Box Model.
7. Identify inherited styles.
8. Identify overridden styles.
9. Determine which CSS rule has higher specificity.
10. Experiment before changing your actual stylesheet.

Changes made in Developer Tools are temporary.

This makes the browser an excellent environment for testing ideas.

---

# 6. Competence Standard

Watching the tutorial alone does **not** demonstrate CSS competence.

Before progressing to the next level, you should be able to:

1. Connect an external stylesheet to an HTML document.
2. Write CSS rules independently.
3. Use element, class, and ID selectors appropriately.
4. Explain the difference between classes and IDs.
5. Explain the CSS Box Model.
6. Explain the difference between margin and padding.
7. Apply borders and backgrounds correctly.
8. Understand basic cascade behavior.
9. Explain inheritance.
10. Explain basic specificity.
11. Style a webpage from an unfamiliar specification.
12. Debug styling problems using Browser Developer Tools.
13. Experiment with CSS using a live playground.
14. Consult MDN documentation independently.
15. Explain your CSS implementation during code review.

---

# 7. Next Learning Stage

Once you are comfortable with CSS foundations, continue to:

## 🟡 Intermediate CSS

### Flexbox

Learn:

* Flex containers
* Flex items
* Main axis
* Cross axis
* `display: flex`
* `justify-content`
* `align-items`
* `gap`
* `flex-direction`
* `flex-wrap`
* `flex-grow`
* `flex-shrink`

### CSS Grid

Learn:

* Grid containers
* Rows
* Columns
* Grid tracks
* `display: grid`
* `grid-template-columns`
* `grid-template-rows`
* `gap`
* Grid placement
* Responsive grid layouts

### Responsive Web Design

Learn:

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

# 🚀 CSS Learning Progression

```text
🟢 CSS Foundations
        ↓
🟡 Flexbox
        ↓
🟡 CSS Grid
        ↓
🟡 Responsive Web Design
        ↓
🔴 Advanced CSS
        ↓
🔴 Professional CSS
        ↓
🏆 Final Competence Project
```

---

## 💡 Learning Principle

> Do not learn CSS by memorizing every property.

Learn how to:

**Read documentation → experiment → inspect the result → identify problems → debug → improve your implementation.**

That is the workflow used in real web development.

