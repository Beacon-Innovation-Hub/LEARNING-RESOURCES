<!--
Beacon Innovation Hub — HTML Learning Path
This TXT file contains GitHub Markdown source.
Copy the contents into a .md file in the BIH learning repository to render it on GitHub.
-->

# Level 4 — HTML Accessibility

> Build HTML that can be understood and operated by a wider range of users and assistive technologies.

**Difficulty:** Intermediate → Advanced

[← Previous Level](Level%203%20—%20Forms%20%26%20Data%20Collection.md) · [Next Level →](Level%205%20—%20HTML%20for%20SEO.md)

---

## Why Accessibility Matters

Accessibility is a core requirement of professional web development.

Good HTML should provide a strong accessible foundation before additional ARIA or JavaScript behaviour is introduced.

---

## Required Documentation

**[MDN — Web Accessibility](https://developer.mozilla.org/en-US/docs/Web/Accessibility)**

**[MDN — HTML: A Good Basis for Accessibility](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Accessibility/HTML)**

---

## Learning Objectives

Understand:

- [ ] Semantic HTML and accessibility
- [ ] Alternative text
- [ ] Accessible links
- [ ] Accessible forms
- [ ] Keyboard accessibility
- [ ] Focus considerations
- [ ] Heading hierarchy
- [ ] Accessible tables
- [ ] Native HTML controls
- [ ] ARIA fundamentals
- [ ] Screen-reader considerations

---

## Core Principle

```text
Native HTML
     ↓
Semantic Structure
     ↓
Keyboard Usability
     ↓
Accessible Names / Labels
     ↓
ARIA only when necessary
```

Do not use ARIA to replace correct native HTML when an appropriate native element already exists.

---

## Practice — Accessibility Audit

Audit one of your previous HTML projects.

Document:

| Problem | Location | Why It Matters | Correction |
|---|---|---|---|
| Example | Image | Missing text alternative | Add meaningful `alt` text |

Investigate:

- Heading order
- Image alternatives
- Link text
- Form labels
- Keyboard navigation
- Table structure
- Native controls
- Semantic landmarks

Correct the problems using semantic/native HTML wherever possible.

---

## Level Completion Checklist

- [ ] I understand why semantic HTML supports accessibility.
- [ ] I can write useful alternative text.
- [ ] I can create accessible forms.
- [ ] I can identify poor link text.
- [ ] I can test basic keyboard usability.
- [ ] I understand when native controls should be preferred.
- [ ] I understand the basic purpose of ARIA.
- [ ] I completed an accessibility audit.

**Next:** [Level 5 — HTML for SEO →](Level%205%20—%20HTML%20for%20SEO.md)
