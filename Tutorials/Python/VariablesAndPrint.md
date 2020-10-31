# Python Tutorial: Variables and Print Statements
[Home](../../README.md) -- [Tutorials](../../Tutorials/README.md) -- [Blog](../../Blog/README.md) -- [About Me](../../aboutme.md) -- [Contact](../../contactme.md) -- [Resume](../../Resume.pdf) -- [Copyright](../../copyright.md)

 March 17, 2020

Go through this tutorial interactively on [Colab](https://colab.research.google.com/drive/1eNGP4ZDTetB3P_dyfrP1Ey9rZbPo1vfb).  Once you follow the link click "Open in Playground" (this does not save your work) or download as an ".ipynb" file and upload it to your own Google Drive if you want to keep your progress.

## Introduction

Python is a programming language.  A programming language is a set of instructions (in words and symbols) that tell a computer what to do. Python is a very popular programming language that people use for work, research, and hobbies.   

## Print Statements

One of the most important things to know how to do is make a computer display something.  In Python, we can do this using the `print` statement followed by a set of parentheses `()`.  The box below shows you how to print words using Python.  Anything that is typed between the single quotes (`'`) will be displayed.  In this case, we are displaying `Hello World`.  You can run the code by clicking the button to the left (looks like a Play button).

``` python
print ('Hello World')
```

Output:
```
Hello World
```

In programming a bunch of letters grouped together using single quotes is called a _string_.  A string has to appear between single quotes (`'`) so that all of the letters are kept together.  The following are all examples of strings:
* `'Hello World'`
* `'Robots'`
* `'J'` (even single letters can be strings!)
* `My age is 24` (numbers can also be in a string!)

Python can also be used to display numbers.  However, for numbers you do not need to use the single quotes (`'`).    For example:

```python
print(2)

print(45)
```

Output:
```
2
45
```

## Variables

A variable in Python is a placeholder for a number or letters.  Strings (letters) must be between single quotes (`'`) but numbers are not.

To create a variable, first you must choose a name for your variable.  The variable name should be a word that describes what your variable is going to hold.  The more descriptive name the better.

First, type your variable name.  Then type an equal sign.  Then on the right side of the equal sign type the value that your variable should hold.

``` python
name = 'Julie'

age = 24
```

The value that is being held in a variable can be displayed using the print statement (just put the name of the variable between the parentheses of the print statement).

``` python
print(name)

print(age)
```

Output:
```
Julie
24
```

Names for variables must start with a letter, but can also contain underscores `_`.  Typically, an underscore is used to separate words in a variable name.

For example, if I want to make my variable names more descriptive I can use:

``` python
my_name = 'Julie'

my_age = 24
```

Variable names can also contain numbers, just as long as the first letter of the name is a letter.

``` python
my_age_2020 = '24'
```

You can overwrite the value stored in a variable by setting it equal to a new value.  For example:

``` python
a = 'Julie'

print (a)

a = 'Hartley'

print(a)
```

Output:
```
Julie
Hartley
```

If you want to keep the values stored in your variables, make sure you are careful about not overwriting them.  Use unique variable names for each value you want to keep!

## Advanced Printing


To make your print statements more clear, you can combine strings and variables in print statements!  To do this you put both things you want to print inside the parentheses of the print statement (in the order you want them to print) and separate them with a comma.  For example:

```python
a = 3

print('The value of a is', a)
```

Output:
```
The value of a is 3
```

You can also do this with more than one variable, you just need to have commas between the individual parts.

``` python
a = 3
b = 4

print ('The value of a is', a, 'and the value of b is', b)
```

Output:
```
The value of a is 3 and the value of b is 4
```


## Copyright Notice
Python Tutorial
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

