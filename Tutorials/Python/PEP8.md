# Python's PEP8 Style Guide

[Home](../../README.md) -- [Tutorials](../../Tutorials/README.md) -- [Blog](../../Blog/README.md) -- [About Me](../../aboutme.md) -- [Contact](../../contactme.md) -- [Resume](../../Resume.pdf) -- [Copyright](../../copyright.md)

November 11, 2020

PEP8 stands for Python Enhancement Proposal #8, which is a set of guidelines to create consistent and easily readable Python code.  Python code will run without following the PEP8 style guide, but it is definitely recommended to follow it.  There are several Python packages, such as Pylint, that will check code for deviations from PEP8.  This post covers the white space and naming conventions suggested by the PEP8 style guide but the PEP8 style guide does include other formatting suggestions.  For a more through explanation of PEP8 recommendation, see the [PEP8 website](https://www.python.org/dev/peps/pep-0008/) or the book _Effective Python_ by Brett Slatkin.

## White Space

### Use spaces instead of tabs to indent and each indentation level should be indented by 4 spaces


```python
def my_function ():
    if 1 == 1:
        print ("If Statement")
```

### Line continuations should be indented by 4 spaces

```python
function_name (argument1, argument2, argument3,
    argument4, argument5)
```

### Functions and classes should be separated by two blank lines in code files

Example of proper function set-up (i.e. each line of the function is indented by four spaces and functions are separated by two lines).

```python
def function1():
    print('function 1')
    
    
def function2():
    print('function 2')
```

If a code file includes more than one class, the classes should also be separate by two blank lines.

```python
class Class1():
    def __init__():
        print ('class 1')
        
        
class Class2():
    def __init__():
        print('class 2')
```

### Methods should be separated by only one line

A method is simply a function that is contained inside of a class.

Proper class set-up with multiple methods:

```python
class Class1():
    def __init():
        print('Initialize Class 1')
        
    def method1 ():
        print('Class 1 Method 1;)
```
### No spaces around lists indices, function calls, or keyword argument assignments

```python
# No space between the list name and the index call
my_list[0]

# No space between the function name and the parathesis around the arguments
my_function(argument1)

# No spaces on either side of the equal sign with assigning values to the arguments
my_function(argument1='one', argument2='two')
```

### Add one space before and after variable assignment

```python
variable_name = 1
```

### Lines should be no more than 79 characters long

Must text editors include a counter to tell how many characers are in a line.  If a line of code needs to be longer than 79 characters, split it onto two lines and use the proper indentation.

## Naming

### Functions, methods, and variable names should be in lowercase_underscore format

```python
def my_function():
    my_variable = 1
```

### Class and exception names should be in UppercaseWord format

```python
class MyClass():
    def __init__():
        print('My Class')
```

```python
raise NameError('SpecificNameError')
```
### Public attribute names shouldn be in lowercase_underscore format, protected attribute names should be in \_leading_underscore_lowercase format, and private attribute names should be in \_\_double_leading_underscore_lowercase format

An attribute is a variable that belongs to a class.  They can either be set directly in the class or defined in the arguments.

```python
def MyClass():
    public_attribute = 'public'
    _protected_attribute = 'protected'
    __private_attribute = 'private'
    
    def __init__():
        print ('My Class')
```

```python
def MyClass():
    def __init__(self, arg1, arg2, arg3):
        self.public_attribute = arg1
        self._protected_attribute = arg2
        self.__private_attribute = arg3
```   

### Module level constant names should be in ALL_UPPERCASE format

A module level constant is a constant that is defined and avaible for use in the entire code file

```python
PI_CONSTANT = 3.1415
```

## Copyright Notice

Python's PEP8 Style Guide

Copyright (C) 2020  Julie Hartley

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
