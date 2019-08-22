# python-code-snippets (documentation link)
# itertools
https://docs.python.org/3/library/itertools.html

# unittest
https://docs.python.org/3/library/unittest.html

# dir(), type(), help(), __version__, __file__
dir() => show method
type() => type of data
help() => description of method
__version__ => version of library imported
__file__ => directory of the library located


# break point (debugger)
https://docs.python.org/3/library/pdb.html

# loggin
https://docs.python.org/3/howto/logging.html#advanced-logging-tutorial

# json
https://docs.python.org/3/library/json.html

# class method
https://docs.python.org/3/reference/datamodel.html#special-method-names
```
@classmethod - class function return instances object which can access constructor
@staticmethod - customize function
@property - acts like a constructor but is not a constructor and set attribute (https://github.com/CoreyMSchafer/code_snippets/blob/master/Object-Oriented/6-property-decorator/oop.py)
```

# class inheritance
https://github.com/CoreyMSchafer/code_snippets/blob/master/Object-Oriented/4-Inheritance/oop-finish.py



# decorator example1 without arguments
https://github.com/CoreyMSchafer/code_snippets/blob/master/Decorators/decorators.py

# decorator example2 with arguments
https://github.com/CoreyMSchafer/code_snippets/blob/master/Python-Decorator-Arguments/decorator-start.py
https://github.com/CoreyMSchafer/code_snippets/blob/master/Python-Decorator-Arguments/decorator-finish.py

# generator
```
def add(num):
    yield (num+num)
```

# try and except 
https://docs.python.org/3/tutorial/errors.html

# re (regular expression)
https://docs.python.org/3/library/re.html

# csv 
https://docs.python.org/3/library/csv.html

# random (for sample data generation)
https://docs.python.org/3/library/random.html

# secret (for cryptography)
https://docs.python.org/3/library/secrets.html

# datetime
https://docs.python.org/3/library/datetime.html
# OS
```
https://docs.python.org/release/3.7.3/library/os.html
```
# Input/Output , formating print
```
https://docs.python.org/3/tutorial/inputoutput.html
```

# sorted
```
https://docs.python.org/3/howto/sorting.html
```


# Comprehension
```
numbers = [1,2,3,4,5,6]
my_list = [ n for n in numbers if n %2 == 0 ]

or
my_list = filter(lambda n: n%2 == 0, numbers)
```

# lambda 

**Description: lambda args : operation** \
```
add = lambda x, y : x + y 
add(1,1)
#Output : 2
```
# Map
**Description: map(function, iterable, ...)** \
```
def add(x):
  return x + 1
    
map(add, [1, 2, 3, 4])
# Output [2, 3, 4, 5]
```
```
map(lambda x : x + 1, [1, 2, 3, 4])
# Output [2, 3, 4, 5]
```
```
list_a = [1, 2, 3]
list_b = [4, 5, 6]
  
map(lambda x, y: x + y, list_a, list_b) # Output: [5, 7, 9]
```

# Filter
**Description: filter(function, iterable)**
```
Construct an iterator from those elements of iterable for which function returns true.
```
