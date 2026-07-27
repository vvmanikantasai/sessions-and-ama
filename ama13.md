# AMA13

### Q: Why React callback? Why do we pass a function without brackets?
**A:** Passing a function without `()` gives React a function reference, so it can call it later (e.g., on a click). Using `()` executes the function immediately during rendering.

### Q: What is the difference between `package.json` and `package-lock.json`?
**A:** `package.json` lists project dependencies and versions you want. `package-lock.json` locks the exact installed versions to ensure consistent installs across environments.

### Q: What happens when we call a method without brackets in JavaScript?
**A:** Without `()`, the function is not executed. It returns a reference to the function, which can be stored or passed as an argument.

### Q: Can we write statements in React?
**A:** Yes, JavaScript statements can be written inside functions, event handlers, or hooks. Inside JSX, only expressions are allowed, not statements like `if` or `for`.

### Q: What is React state?
**A:** State is a built-in object that stores data specific to a component. Updating state causes the component to re-render with the new data.

### Q: Which method is used to resolve function ambiguity in Python?
**A:** Python uses **MRO (Method Resolution Order)** to resolve which method to call when multiple parent classes define the same method. You can view it using `ClassName.mro()`.


### Q: Why is React fast?
**A:** React uses a Virtual DOM to compare changes and updates only the necessary parts of the real DOM, reducing expensive DOM operations.

### Q: What is optional chaining?
**A:** Optional chaining (`?.`) safely accesses nested object properties. If a value is `null` or `undefined`, it returns `undefined` instead of throwing an error.
