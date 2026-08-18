# Level 7 — Professional JavaScript

> **Difficulty:** Advanced

[← Previous](<06 - Level 6 - Advanced JavaScript.md>) · [Next Level →](<08 - Level 8 - Real World Projects.md>)

---

At this stage, the objective changes from simply writing working JavaScript to writing JavaScript that is:

> **Readable → Maintainable → Testable → Debuggable → Secure**

---

## 📚 Primary Reference

### MDN JavaScript

**[📘 MDN JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)**

Use MDN increasingly as your primary JavaScript reference.

---

## 🧱 Code Organization

Learn:

* Separation of concerns
* Reusable functions
* Modules
* File organization
* Naming conventions
* Clean functions
* Avoiding unnecessary global variables
* Error handling
* Input validation

---

## 📦 npm

Learn how JavaScript projects manage external packages.

**[📘 npm Documentation](https://docs.npmjs.com/)**

Understand:

```text
npm
package.json
dependencies
devDependencies
package-lock.json
scripts
```

---

## 🔍 ESLint

Learn how static analysis helps identify JavaScript problems.

**[📘 ESLint Documentation](https://eslint.org/docs/latest/)**

Understand:

* Linting
* Rules
* Configuration
* Code-quality checks
* Common JavaScript mistakes

---

## 🧪 Testing

Learn the fundamentals of automated testing.

Start with:

* Unit tests
* Assertions
* Test cases
* Expected vs actual results
* Testing pure functions
* Testing edge cases

Recommended documentation:

**[📘 Vitest Documentation](https://vitest.dev/guide/)**

Example idea:

```javascript
function add(a, b) {
    return a + b;
}
```

Instead of manually checking it every time, create automated tests for:

```text
add(2, 2)
add(-1, 1)
add(0, 0)
add(1.5, 2.5)
```

---

## 🐛 Debugging

Learn to use Browser Developer Tools for:

* Breakpoints
* Step execution
* Watching variables
* Call stack inspection
* Network requests
* Console errors
* Performance investigation

Do not rely only on `console.log()`.

---

## 🔐 JavaScript Security Fundamentals

Understand:

* Never trusting user input
* Input validation
* Output encoding concepts
* XSS fundamentals
* Unsafe `innerHTML`
* Sensitive information in frontend JavaScript
* API key exposure
* Third-party dependencies
* Dependency security

Use:

**[📘 OWASP — Cross Site Scripting Prevention](https://owasp.org/www-community/attacks/xss/)**

---

---

## Level Completion Checklist

- [ ] I completed the learning resources.
- [ ] I read the required documentation.
- [ ] I completed the exercises and practice activities.
- [ ] I can explain the major concepts without relying on a tutorial.
- [ ] I can apply the concepts to a new problem.

[Next Level →](<08 - Level 8 - Real World Projects.md>)
