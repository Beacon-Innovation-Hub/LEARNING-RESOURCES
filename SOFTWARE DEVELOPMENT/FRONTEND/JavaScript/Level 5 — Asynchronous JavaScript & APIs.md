# Level 5 — Asynchronous JavaScript & APIs

> **Difficulty:** Intermediate → Advanced

[← Previous](<04 - Level 4 - Modern JavaScript ES6.md>) · [Next Level →](<06 - Level 6 - Advanced JavaScript.md>)

---

Modern web applications constantly communicate with servers.

This requires understanding asynchronous JavaScript.

---

## 🎥 Learning Resources

### Async JavaScript Playlist

**[▶ Async JavaScript Course](https://www.youtube.com/playlist?list=PL4cUxeGkcC9jx2TTZk3IGWKSbtugYdrlu)**

[![Async JavaScript](https://img.youtube.com/vi/ZYb_ZU8LNxs/maxresdefault.jpg)](https://youtu.be/ZYb_ZU8LNxs)

**[▶ Watch Resource](https://youtu.be/ZYb_ZU8LNxs)**

[![JavaScript APIs](https://img.youtube.com/vi/Q-Zmc0E0GYY/maxresdefault.jpg)](https://youtu.be/Q-Zmc0E0GYY)

**[▶ Watch Resource](https://youtu.be/Q-Zmc0E0GYY)**

[![JavaScript APIs](https://img.youtube.com/vi/XHokFQeQ6Lk/maxresdefault.jpg)](https://youtu.be/XHokFQeQ6Lk)

**[▶ Watch Resource](https://youtu.be/XHokFQeQ6Lk)**

---

## 🎯 Learn

* Synchronous JavaScript
* Asynchronous JavaScript
* Callbacks
* Promises
* Promise states
* `.then()`
* `.catch()`
* `async`
* `await`
* `fetch()`
* JSON
* APIs
* HTTP fundamentals
* GET
* POST
* HTTP status codes
* `try...catch`
* Loading states
* Error states
* Handling failed requests

---

## 📚 Documentation

**[📘 MDN — Asynchronous JavaScript](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Async_JS)**

**[📘 MDN — Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)**

**[📘 MDN — Using Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises)**

---

# 🧪 API Practice

Start with a simple request:

```javascript
async function getData() {
    try {
        const response = await fetch("API_URL");

        if (!response.ok) {
            throw new Error("Request failed");
        }

        const data = await response.json();

        console.log(data);
    } catch (error) {
        console.error(error);
    }
}
```

Understand every line before moving forward.

---

## 🧩 API Exercises

Build these progressively:

### 1. Random Quote Generator

```text
API
 ↓
Fetch quote
 ↓
Display quote
 ↓
New Quote button
```

### 2. GitHub Profile Viewer

Allow the user to enter a GitHub username.

Display:

* Avatar
* Username
* Biography
* Followers
* Following
* Public repositories

### 3. Country Explorer

Allow users to search countries and display:

* Flag
* Capital
* Population
* Region
* Languages

### 4. Weather Application

Allow users to enter a city and display weather information.

Your interface should handle:

```text
Loading
Success
No results
API failure
Network failure
```

---

---

## Level Completion Checklist

- [ ] I completed the learning resources.
- [ ] I read the required documentation.
- [ ] I completed the exercises and practice activities.
- [ ] I can explain the major concepts without relying on a tutorial.
- [ ] I can apply the concepts to a new problem.

[Next Level →](<06 - Level 6 - Advanced JavaScript.md>)
