# 🐍 Python - Functions

## Day 4 Topic

### Syntax

```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Krishna"))
# Output: Hello, Krishna!
```

### *args (Multiple Arguments)

```python
def sum_all(*args):
    total = 0
    for num in args:
        total += num
    return total

print(sum_all(1, 2, 3, 4))
# Output: 10
```

### **kwargs (Keyword Arguments)

```python
def user_info(**kwargs):
    for key, value in kwargs.items():
        print(f"{key}: {value}")

user_info(name="Krishna", age=25, role="Engineer")
# Output:
# name: Krishna
# age: 25
# role: Engineer
```

### Default Parameters

```python
def greet(name, message="Hello"):
    return f"{message}, {name}!"

print(greet("Krishna"))           # Hello, Krishna!
print(greet("Krishna", "Hi"))     # Hi, Krishna!
```

---

## 🔗 Related

- [[list-comprehensions]] - Next topic
- [[modules]] - Importing code
