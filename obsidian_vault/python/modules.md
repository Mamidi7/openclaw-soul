# 📦 Python - Modules

## What is a Module?

A Python file (`.py`) that contains functions, classes, or variables.

```python
# mymodule.py
def add(a, b):
    return a + b
```

## Importing

```python
import mymodule
print(mymodule.add(2, 3))  # 5
```

## From Import

```python
from mymodule import add
print(add(2, 3))  # 5
```

## Alias

```python
import mymodule as mm
print(mm.add(2, 3))  # 5
```

## Common Modules

| Module | Purpose |
|--------|---------|
| `os` | Operating system |
| `json` | JSON handling |
| `datetime` | Date/time |
| `random` | Random numbers |
| `requests` | HTTP requests |

---

## 🔗 Related

- [[functions]] - Previous topic
- [[list-comprehensions]] - Next topic
