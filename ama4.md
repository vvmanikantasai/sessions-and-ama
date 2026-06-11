# ama4

## What is the difference between `querySelector()` and `querySelectorAll()`?

`querySelector()` returns the first matching element, while `querySelectorAll()` returns all matching elements.

**Example:** `document.querySelectorAll(".box")`

---

## What is the output of the following code?

```js
console.log("A");
setTimeout(() => console.log("B"), 0);
console.log("C");
```

**Answer:** `A C B`

---

## In how many ways can we access HTML elements in JavaScript?

Common methods are `getElementById()`, `getElementsByClassName()`, `getElementsByTagName()`, `querySelector()`, and `querySelectorAll()`.

**Example:** `document.getElementById("demo")`

---

## What are the two main points when working with recursion?

1. Base case
2. Recursive call

**Example:** `factorial(n - 1)`

---

## What is the difference between a callback and a higher-order function?

A callback is a function passed as an argument. A higher-order function accepts or returns functions.

**Example:** `setTimeout(myFunc, 1000)`

---

## What is localStorage in the browser?

A browser storage mechanism used to store key-value pairs permanently.

**Example:** `localStorage.setItem("name", "John")`

---

## What is destructuring?

A way to extract values from arrays or properties from objects into variables.

**Example:** `const { name } = user;`

---

## What is promise chaining?

Using multiple `.then()` methods one after another on a promise.

**Example:** `promise.then(fn1).then(fn2)`

---

## What is the root element of the DOM tree?

The `<html>` element.

**Example:** `document.documentElement`

---

## What are the states of a Promise?

* Pending
* Fulfilled
* Rejected

**Example:** `Promise.resolve("Success")`

---

## What is throttling?

A technique that limits how frequently a function executes.

**Example:** Scroll event throttling.

---

## What is the difference between `innerHTML` and `textContent`?

`innerHTML` parses HTML tags, while `textContent` treats everything as plain text.

**Example:** `element.textContent = "<h1>Hello</h1>"`

---

## What is the difference between `call()` and `apply()`?

`call()` accepts arguments separately, while `apply()` accepts arguments as an array.

**Example:** `fn.apply(obj, [1, 2])`

---

## How can we get `NaN` in the console?

By performing an invalid numeric operation.

**Example:** `"abc" * 2`
