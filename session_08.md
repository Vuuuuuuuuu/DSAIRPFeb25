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
```python
open("file.txt", "r")
with open("sample.txt", "w") as f:
f.write("hello world !")
data=f.readlines
print(data)
```
### misc function
#### defining and calling function
- use def function_name() to define function
- call a function using function_name
#### function arguments
```python
def add(a, b): 
     print("sum:", a+b)
```
 #### return value
```python return()```
#### scope of variables in function
```python
x= 5 #global scope
def my_funct():
   x= 5#local variable
   print("inside function:", x)
```
#### documentation
```python print{add numbers, __doc__}```
####
- to store any number od elements
- use kwargs
```python
def print_info(*kwargs):
   for item in  kwargs
   print(item)
```
 
## Custom Functions
