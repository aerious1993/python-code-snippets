# python-code-snippets

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
