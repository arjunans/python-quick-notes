# python-quick-notes

## 1. How to print text in python?
```python
   print("Hello, World!")
```

## 2. To check if you have python installed on a Windows PC, search in the start bar for Python or run the following on the Command Line.
```
python --version
```

## 3. Comments starts with a #, and Python will ignore them:
```python
#This is a single-line comment
print("Hello, World!")
```
## 4. Multiline comment:
```python
"""
This is a comment
written in
more than just one line
"""
print("Hello, World!")
```

## 5. How to assign variables in python?
```python
x = 5
y = "John"
print(x)
print(y)
```

## 6. If you want to specify the data type of a variable, this can be done with casting.
```python
x = str(3)    # x will be '3'
y = int(3)    # y will be 3
z = float(3)  # z will be 3.0
```

## 7. You can get the data type of a variable with the type() function.
```python
x = 5
y = "John"
print(type(x))
print(type(y))
```

## 8. String variables can be declared either by using single or double quotes:
```python
x = "John"
# is the same as
x = 'John'
```

## 9. Variable names are case-sensitive.
A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:
 - A variable name must start with a letter or the underscore character
 - A variable name cannot start with a number
 - A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
 - Variable names are case-sensitive (age, Age and AGE are three different variables)
 - A variable name cannot be any of the Python keywords.
```python
a = 4
A = "Sally"
#A will not overwrite a

#Some legal variable names
myvar = "John"
my_var = "John"
_my_var = "John"
myVar = "John"
MYVAR = "John"
```
