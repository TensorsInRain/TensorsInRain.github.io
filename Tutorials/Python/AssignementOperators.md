# Python Tutorial: Changing the Value of a Variable using Assignment Operators

[Home](../../README.md) -- [Tutorials](../../Tutorials/README.md) -- [Blog](../../Blog/README.md) -- [About Me](../../aboutme.md) -- [Contact](../../contactme.md) -- [Resume](../../Resume.pdf) -- [Copyright](../../copyright.md)

November 9, 2020

Go through this tutorial interactively on [Colab](https://colab.research.google.com/drive/1bC4FSL3vaDw7dOX1kM0MRrNYBE0hG7PE?usp=sharing).  Once you follow the link click "Open in Playground" (this does not save your work) or download as an ".ipynb" file and upload it to your own Google Drive if you want to keep your progress.

Lets say we have a variable that is equal to a number, but we want to change that variable by doing some type of math to it. The most obvious way to accomplish this task is:

``` python
# initialize the variable a to be the number 5
a = 5

print(a)

# Add 5 to the number stored in a 
# So it would be 5+5
# store the result back in the variable a
a = a + 5

print(a)
```

Output:
```
5
10
```
Python offers a cleaner way of doing the exact same thing using _assignment operators_.  If you want to add a number to an already existing variable you can use the addition assignement operator:

``` python
a = 5

# This is the same as a = a + 5
a += 5

print (a)
```

Output:
```
10
```

In the above code `a += 5` is equivalent to the `a = a + 5` line in the previous code section, but is in a more compact form.  This means that it is faster to type, especially if you have a long variable name.

There are also assignment operators for subtraction, multiplication, and division:

``` python
 # Initialize the value of a
 a = 1

# This is the same as a = a + 2
 a += 2

 print (a)

# This is the same as a = a - 1
 a -= 1

 print (a)

# This is the same as a = a * 3
 a *= 3

 print (a)

# This is the same as a = a / 2
 a /= 2

 print (a)
```

Output:
```
3
2
6
3.0
```

Assignment operators can be very useful and are pretty common so being familiar with them will help you in your ability to read Python code and to write your own.

## Copyright Notice
Python Tutorial: Changing the Value of a Variable using Assignment Operators
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
along with this program.  If not, see <https://www.gnu.org/licenses/>
