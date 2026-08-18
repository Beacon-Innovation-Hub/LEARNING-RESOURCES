# Level 6 — Advanced JavaScript

> **Difficulty:** Advanced

[← Previous](<05 - Level 5 - Async JavaScript and APIs.md>) · [Next Level →](<07 - Level 7 - Professional JavaScript.md>)

---

At this stage, focus on understanding **why JavaScript behaves the way it does**.

---

## 🎥 Learning Resources

[![Advanced JavaScript](https://img.youtube.com/vi/vKJpN5FAeF4/maxresdefault.jpg)](https://youtu.be/vKJpN5FAeF4)

**[▶ Watch Resource](https://youtu.be/vKJpN5FAeF4)**

[![Advanced JavaScript](https://img.youtube.com/vi/rR_B-m95ljk/maxresdefault.jpg)](https://youtu.be/rR_B-m95ljk)

**[▶ Watch Resource](https://youtu.be/rR_B-m95ljk)**

[![Advanced JavaScript](https://img.youtube.com/vi/pJ_oKVFHMK0/maxresdefault.jpg)](https://youtu.be/pJ_oKVFHMK0)

**[▶ Watch Resource](https://youtu.be/pJ_oKVFHMK0)**

[![Advanced JavaScript](https://img.youtube.com/vi/C1PZh_ea-7I/maxresdefault.jpg)](https://youtu.be/C1PZh_ea-7I)

**[▶ Watch Resource](https://youtu.be/C1PZh_ea-7I)**

---

## 🎯 Study

* Execution context
* Call stack
* Lexical scope
* Scope chain
* Closures
* Hoisting
* `this`
* Prototypes
* Prototype chain
* Classes
* Higher-order functions
* Pure functions
* Immutability
* Event loop
* Tasks
* Microtasks
* Shallow copying
* Deep copying
* Memory fundamentals

---

## 📚 Advanced Documentation

**[📘 MDN — Closures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Closures)**

**[📘 MDN — Object Model](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Inheritance_and_the_prototype_chain)**

**[📘 MDN — Event Loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Event_loop)**

---

# 🧩 Advanced Experiments

Do not simply read these concepts.

Write small programs to investigate them.

### Closure

```javascript
function createCounter() {
    let count = 0;

    return function () {
        count++;
        return count;
    };
}

const counter = createCounter();
```

Predict the output before running the function multiple times.

Explain why `count` continues to exist.

---

### Event Loop

Predict the output order:

```javascript
console.log("A");

setTimeout(() => {
    console.log("B");
}, 0);

Promise.resolve().then(() => {
    console.log("C");
});

console.log("D");
```

Run it only after making your prediction.

Then explain the result.

---

---

## Level Completion Checklist

- [ ] I completed the learning resources.
- [ ] I read the required documentation.
- [ ] I completed the exercises and practice activities.
- [ ] I can explain the major concepts without relying on a tutorial.
- [ ] I can apply the concepts to a new problem.

[Next Level →](<07 - Level 7 - Professional JavaScript.md>)
