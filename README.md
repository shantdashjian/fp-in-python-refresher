# Functional Programming in Python Refresher

A repo to brush up on FP using Python.

## In This Document:
  - [What is Functional Programming](what-is-functional-programming)
  - [Why Functional Programming](why-functional-programming)
  - [FP Concepts](fp-concepts)

## What is Functional Programming
- It's a way to program using functions to transform data.
- It's declarative, focused on the **what**.
- Python is not a pure FP language, but we can use Python to learn the key concepts in FP.
- Purer FP languages include: Haskell, Clojure, OCamel, Scala.
- In FP, data is **immutable**. Tuples are immutable.
- Out of the 4 key concepts in OOP, only **inheritance** is not possible in FP. Inheritance requires mutable classes.
- Use OOP for modeling objects and concepts. It's why it's used in:
  - Game programming
  - Simulations
  - UI
 
## Why Functional Programming
- It's easier to debug.
- When debugging, break it down to pieces, print the outcome of each, then when fixed, put things back together.

## FP Concepts
### 1. Functions as First Class Citizens
- In Python, functions are first class citizens, i.e. they are treated as regular values tha can be assigned to variables.
- `add_one = lambda a: a + 1`

### 2. Higher Order Functions
- HOFs receive functions as parameter values and return functions as return values
- Key HOFs: map, filter, reduce. They take a funciton, and an iterable, and return an iterable.

### 3. Pure Functions
- PFs are deterministic. Given the same input, they produce the same output.
- They have no side effects. They do not impact the state outside of them. They do no I/O.
- No-op functionas return nothings.

### 4. Memoization
- Memoization is using a memo/cache to remember the results of past calculations. It's trading space for better speed.

### 5. Referential Transparency
- RT is to always be able to replace a function call with its return value(s).
