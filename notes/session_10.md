# Loops & Functions in Python
## For Loop
For loops can be applied on any sequential object (list, string, tuple, range, etc.)
```python
for char in "Hello":
    print(char)
```

```python
for i in range(10):
    print(i)
```

[![Python For Loop](https://img.youtube.com/vi/oywGQ0wVJQs/0.jpg)](https://youtu.be/oywGQ0wVJQs)


## While Loop
```python
i = 1
while i<=10:
  print(i)
  i = i+1
```

[![Python For While Loop](https://img.youtube.com/vi/6mKpZdIfnew/0.jpg)](https://youtu.be/6mKpZdIfnew)


### Continue
### Break
[![Python Continue-break](https://img.youtube.com/vi/Vv8YQqvg4KQ/0.jpg)](https://youtu.be/Vv8YQqvg4KQ)

### Pass Keyword

# Functions in Python

## Built-in Functins

## Custom Functions
```python
def greet():
  return "Good morning"
greet()
```

```python
def add(a,b):
  c = a+b
  return c
z = add(2,4)
print(z)
```
### Function arguments
### Default arguments
```python
def add(a,b=10):
  c = a+b
  return c

z = add(2)
print(z)
```
### kwargs

### Function return values

```python
def simple_arithmetic(a,b):
  return a+b, a-b, a*b, a/b

tsum, tdiff, tmul, tdiv = simple_arithmetic(10,5)
print(tsum, tdiff, tmul, tdiv)
```

# Basic Library Usage
## Keyword library

# Creating and Using Custom Modules

# File Handling
## OS Library usage