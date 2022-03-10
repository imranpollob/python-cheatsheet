# Python Cheatsheet
The reason behind creating this repository is,
getting up and running with Python within 1 hour.

This cheatsheet will work as a refresher to Python language.

## Basic data types

### Boolean

```python
# Either 'True' or 'False'
x = True
y = False
# Shortcut variable assignment
x, y = True, False
# Statement
print(x and not y) # True
print(not x or y and x) # False
# Condition
if 1 < 2 and 0 <= 1 and 3 > 2 and 2 >=2 and 1 == 1 and 1 != 0: # True
if None or 0 or 0.0 or '' or "" or [] or {} set(): # False
```

### Integer and Float

```python
x = 4 # int
y = 2 # int
z = 1.5 # float
# Arithmetic operations
print(x + y) # 6
print(x - y) # 6
print(x * y) # 6
print(x / y) # 6
print(x // y) # 6
print(x % y) # 6
print(x ** y) # 6
print(-x) # 6
print(abs(-x)) # 6
print(int(z)) # 6
print(float(x)) # 6
print(round(z)) # 6
import math
print(math.ceil(z)) # 6
print(math.floor(z)) # 6
print(math.pow(x, y)) # 6
```