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
print(x - y) # 2
print(x * y) # 8
print(x / y) # 2.0 dividing always produce float value
print(x // y) # 2 gives intger quotient 
print(x % y) # 0 gives remainder
print(x ** y) # 16 gives power 4*4
print(-x) # -4
print(abs(-x)) # 4 gives absolute value
print(int(z)) # 1 converts to integer
print(float(x)) # 4.0 converts to float
print(round(z)) # 2 rounds the number
import math
print(math.ceil(z)) # 2 
print(math.floor(z)) # 1
print(math.pow(x, y)) # 16 calculate power
```