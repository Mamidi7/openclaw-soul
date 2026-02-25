# 📝 Python - List Comprehensions

## What?

A compact way to create lists in one line.

## Basic Syntax

```python
# Old way
squares = []
for i in range(5):
    squares.append(i ** 2)

# New way (list comprehension)
squares = [i ** 2 for i in range(5)]
# [0, 1, 4, 9, 16]
```

## With Condition

```python
# Only even numbers
evens = [i for i in range(10) if i % 2 == 0]
# [0, 2, 4, 6, 8]
```

## Dictionary Comprehension

```python
# Square each number
d = {i: i**2 for i in range(3)}
# {0: 0, 1: 1, 2: 4}
```

## Set Comprehension

```python
s = {i**2 for i in range(5)}
# {0, 1, 4, 9, 16}
```

---

## 🔗 Related

- [[functions]] - Previous topic
- [[modules]] - Previous topic
