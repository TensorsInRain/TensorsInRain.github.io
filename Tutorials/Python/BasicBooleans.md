# Python Tutorial: Basic Booleans

[Home](../../README.md) -- [Tutorials](../../Tutorials/README.md) -- [Blog](../../Blog/README.md) -- [About Me](../../aboutme.md) -- [Contact](../../contactme.md) -- [Resume](../../Resume.pdf) -- [Copyright](../../copyright.md)

November 12, 2020

Go through this tutorial interactively on [Colab](https://colab.research.google.com/drive/1ZikNmNpqwd6rxcVCuLj_LUwqT8KwZc3D?usp=sharing).  Once you follow the link click "Open in Playground" (this does not save your work) or download as an ".ipynb" file and upload it to your own Google Drive if you want to keep your progress.


So far in Python we have used three different types of data: whole numbers (known as ints), numbers with a decimal place (known as floats), and strings.  In basic Python there is another type of data known as a boolean.  A boolean can take on only two values: `True` or `False` (note that they have to start with a capital letter).

``` python
my_boolean = True

my_boolean_2 = False
```

The value can also be assigned to a boolean using the types of conditions used in the if statements above.  For example:

``` python 
condition = 100 < 1

print (condition)
```

Output:
```
False
```

Booleans can also be used as the condition of an if statement.

``` python
# Creating a boolean
condition = True

print (condition)

# Using the boolean in an if statement
# The if statement should run
if condition:
    print ('The condition is True')

# Overwrite the value of the boolean
condition = False

print (condition)

# The if statement will not run
if condition:
    print ('The condition is True')
```

Output:
```
True
The condition is True
False
```

Booleans can also be created using variables.  Let's say you have a variable that contains a number and you want to know if the number is 2 or some other number.  You could use the following code to check and see if your variable contains the number 2.

``` python
my_number = 3

is_my_number_2 = my_number == 2

print ('My number is 2:', is_my_number_2)
```

Output:
```
My number is 2: False
```

A standard convention in many programming languages is to name a boolean starting with the word `is` and followed by a short phrase that describes what the boolean is for.  So above my boolean has the name `is_my_number_2`.  Anyone reading my code could tell that that variable has to deal with telling if my number is equal to two.  This is an example of how good variable names make your code easier to read!

## Copyright Notice
Python Tutorial: Basic Booleans
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
