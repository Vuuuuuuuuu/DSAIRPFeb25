# Functions in Python
- bulit in function
- custom function
## Built-in Functins
- type convertion
- input and output functions
- mathemathical functions
- itterables and sequences function
- obeject and memory function
- file handling function
- miscellaneous function
### type convertion
- int()
- str()
- float()
- bool()
- list()
- tuple()
- set()
- dict([(),()])
### input  and output function
- input()
- print()
### mathemethical functions
- abs()
- pow(a,b)
- round()
- divmod(a,b)
### iterable and sequences
- len()
- max()
- min()
- sum()
- sorted()
- range()
### object and memory funtions
- type()
- id()
- isinstance()
- dir()
### file handling function
open("file.txt", "r")<br>
with open("sample.txt", "w") as f:<br>
f.write("hello world !")<br>
<br>
data=f.readlines<br>
print(data)
### misc function
#### defining and calling function
- use def function_name() to define function
- call a function using function_name
#### function arguments
 def add(a, b): <br>
     print("sum:", a+b)
 #### return value
 return()
#### scope of variables in function
x= 5 #global scope <br>
def my_funct():<br>
   x= 5#local variable <br>
   print("inside function:", x) <br>
#### documentation
print{add numbers, __doc__}
####
- to store any number od elements
- use kwargs
```python
def print_info(*kwargs)<br>
   for item in  kwargs<br>
   print(item)<br>
```
 
## Custom Functions
