# Python Tutorial: User Input

[Home](../../README.md) -- [Tutorials](../../Tutorials/README.md) -- [Blog](../../Blog/README.md) -- [About Me](../../aboutme.md) -- [Contact](../../contactme.md) -- [Resume](../../Resume.pdf) -- [Copyright](../../copyright.md)

March 19, 2020

Go through this tutorial interactively on [Colab](https://colab.research.google.com/drive/1fS7xoRnbEaqC8nMb2i6nHLNALkogAUEK).  Once you follow the link click "Open in Playground" (this does not save your work) or download as an ".ipynb" file and upload it to your own Google Drive if you want to keep your progress.

A common thing to do when writing a program is to ask the person using your code for some type of input.  Python does this by having the user type into the console (the place below your code where things are printed).  You can store a users input in a variable and use it later.

Python asks for user input using this bit of code : `input()`.  You can set this bit of code equal to a variable if you want to store it.  For example:

``` python
user_input = input()
```

A box will appear in the console, prompting the user to type in their response.

Once we have stored the user input into a variable (`user_input`) we can print the variable to see what value it holds.

``` python
print (user_input)
```

Output:
```
Whatever was entered earlier
```

Python saves the input as a _string_ even if its a number. If you want Python to save the input as a number you have to specifically tell it to make a *conversion*. 

For example if you want to save the inputted number as an integer (a number without a decimal point) you can place the `input()` inside parentheses with `int` before the parentheses.

``` python
a = int(input())
```

If you want to save your number as a float (a number with a decimal point) you can use the same format but replace `int` with `float`.  

``` python
a = float(input())
```

`int` and `float` are both datatypes in the Python programming language.  We will get into datatypes in a later tutorial.  For now all you need to know is an `int` is an integer (a whole number) and a `float` is a decimal number.


## Copyright Notice
Python Tutorial: User Input
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





