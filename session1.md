# Unit Testing in Python

## What is Unit Testing?

Unit Testing is a software testing method used to test small parts of a program, such as functions or methods, to check whether they work correctly.

## Why do we use Unit Testing?

- To find bugs early
- To save testing time
- To check whether code still works after changes
- To improve code reliability

### Real-Time Example: Calculator Testing

In this example, we are testing calculator functions like addition and subtraction.

## Code Example

### calculator.py

```python
def add(a, b):
    return a + b


def subtract(a, b):
    return a - b
```

### test_calculator.py

```python
import unittest
from calculator import add, subtract


class TestCalculator(unittest.TestCase):

    def test_add(self):
        result = add(10, 5)
        self.assertEqual(result, 15)

    def test_subtract(self):
        result = subtract(10, 5)
        self.assertEqual(result, 5)


if __name__ == "__main__":
    unittest.main()
```

---

# Step-by-Step Explanation

## Step 1: Importing unittest

```python
import unittest
```

- `unittest` is Python’s built-in testing module.
- It helps us create and run tests.

---

## Step 2: Importing Functions

```python
from calculator import add, subtract
```

- Imports functions from `calculator.py`
- These functions will be tested.

---

## Step 3: Creating Test Class

```python
class TestCalculator(unittest.TestCase):
```

- A class used for writing test cases.
- `TestCase` provides testing features.

---

## Step 4: Writing Test Function

```python
def test_add(self):
```

- Tests the `add()` function.
- Test methods should start with `test_`.

---

## Step 5: Calling Function

```python
result = add(10, 5)
```

- Calls the function.
- Stores output in `result`.

---

## Step 6: Checking Expected Output

```python
self.assertEqual(result, 15)
```

- Checks if actual output matches expected output.
- If equal → Test Passed
- If not equal → Test Failed

---

## Step 7: Running Tests

```python
unittest.main()
```

- Runs all test cases automatically.

---

# Running the Program

Command:

```bash
python -m unittest test_calculator.py
```

### Output

```text
..
----------------------------------------------------------------------
Ran 2 tests

OK
```

### Meaning

- `..` → Two tests passed
- `OK` → All tests successful

---

# Failed Test Example

If we accidentally change:

```python
def add(a, b):
    return a - b
```

### Output

```text
FAIL
AssertionError
```

Unit testing immediately detects the mistake.

---

# Advantages of Unit Testing

- Finds bugs early
- Saves time
- Improves code quality
- Easier maintenance

---

# Real-Time Uses of Unit Testing

- Login Systems
- Payment Systems
- Banking Applications
- Shopping Websites

---

# Conclusion

Unit Testing helps developers automatically test small parts of code.

In this example:

- We tested calculator functions
- Verified correct output
- Detected mistakes automatically

Thank You
