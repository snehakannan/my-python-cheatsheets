# Base Python Notes/useful functions for Data Analysis

#### Two ways to print numbers within print
```
print('First Number is {} and Second Number is {}'.format(1, 2))
print('First Number %s, Second Number %s' %(1, 2))
```

#### Slicing
```
s = 'abcdefg'
s[0:] # From 0th element abcdefg
s[:3] # Up till element before position 3 abc (0 to 2)
s[0:3] # abc
```

#### List 
```
my_list = ['a', 'b', 'c']
my_list.append('d')
# my_list is now ['a', 'b', 'c', 'd']
my_list[0] = 'ABC'
# my_list is now ['ABC', 'b', 'c', 'd']
```

#### Dictionary
```
my_dict = {'key1':'value', 'key2':123}
my_dict['key1']
# Keys can be of any data type
my_dict = {1:'value', 'key2':123}
print(my_dict[1]) 
```

#### Tuple
```
# Tuples are immutable
my_tuple = (0, 1, 2)
my_tuple[0] = 'NEW' # will return error. This is the difference between list and tuple
```

#### Set
```
Set will only have unique elements.
set([1, 2, 3, 4, 5, 1, 2, 3]) will return only unique elements
s = {1, 2, 3, 1, 2}
s will be {1, 2, 3}
s.add(3) no Change in the set
```

#### if, elif, else
```
if condition:
    abcd = 1
elif:
    def
else:
```

#### For
```
seq = [1, 2, 3, 4, 5]
for num in seq:
    print(num)
```

#### While
````
i = 1
while i < 5:
    print(i)
    i = i+ 1 
````

#### Range
```
for x in range(0,5):
    print(x)
    
list(range(0, 5)) = [0, 1, 2, 3, 4]
```

#### List Comprehension
```
x = [1, 2, 3, 4]
[num**2 for num in x] will print [1, 4, 9, 16]
out = [num**2 for num in x]
```

#### Functions
```
def my_function(name = 'Default Name'):
    """
    Docstring
    Contains more Information about the function
    """
    print('Hello '+name)

my_function('Name') # will print Hello Name
```

#### Map 
```
#Map function to sequence
seq = [1, 2, 3, 4, 5]
list(map(lambda num: num*3, seq)) 
[3, 6, 9, 12, 15]
```

#### Filter
```
seq = [1, 2, 3, 4, 5]
list(filter(lambda num:num%2 == 0, seq))
[2, 4]
```

#### String Methods
```
s = 'Some random string #stringmethods'
s.lower()
s.upper()
s.split() s.split(#)[1] stringmethods
```

#### Dictionary
```
d = {'k1': 1, 'k2':2}
# No retain order
d.keys()
d.values()
```

#### List 
```
lst = [1, 2, 3, 4, 5]
item = lst.pop()
print(item) # 5
lst = [1, 2, 3, 4]

first = lst.pop(0)
print(first) 1
lst = [2, 3, 4]

lst.append(5)
lst = [2, 3, 4, 5]
```

#### In Operator
```
'x' in [1, 2, 3]
False
'x' in ['1', 'b', 'x']
True
```

#### Tuple Unpacking
```
x = [(1, 2), (3, 4), (5, 6)]
for (a, b) in x:
    print 'a = %s' %(a) + 'b = %s' %(b)
```

#### Useful shortcuts in Jupyter
```
Shift + Tab => More info about functions
Shift + Enter => Execute
Alt + Enter = Insert Cell
```

#### Python uses 'and' 'or' as logical operators. It does not have && ||