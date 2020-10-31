# Python Tutorial: If Statements

[Home](../../README.md) -- [Tutorials](../../Tutorials/README.md) -- [Blog](../../Blog/README.md) -- [About Me](../../aboutme.md) -- [Contact](../../contactme.md) -- [Resume](../../Resume.pdf) -- [Copyright](../../copyright.md)

March 19, 2020

Go through this tutorial interactively on [Colab](https://colab.research.google.com/drive/1MltLPkkSM9q97ZvKrdOLY3K1LkGJUAJP).  Once you follow the link click "Open in Playground" (this does not save your work) or download as an ".ipynb" file and upload it to your own Google Drive if you want to keep your progress.

In programming an if statement is what is known as a _conditional statement_.  This means that it will only run if a certain condition is true.  An if statement has the following format:

```
if condition:
    # This code runs if condition is true
    Some code
```

An if statement always starts with the word `if`.  This tells Python that you are setting up an if statement.  Following the `if` is a condition, also known as a _boolean_.  This is a statement that is either true or false.  Examples of booleans include `100 < 1` (which is false) and `2 == 2` (which is true).  When creating a condition or boolean in which two values are compared to see if they are equal, a double equal sign is always used.

Immediately after the condition of the if statement is a colon.  This tells Python that the condition is finished and its time to move onto the code.  Note that the code below the if statement is indented.  In Python _whitespace_ (indents) are very important.  They must be there for the code to work properly.  Typically one indents code using 4 spaces, but you can also use the Tab key or any number of spaces.  However, it is very important that you indent the same way each time (i.e. either the same number of spaces or use the Tab key).  Python will see an error if code is not properly indented and will not run.


Now that we have gone over the basic structure of a Python if statement, lets create some!  The following are all examples of if statements.

``` python
if 100 < 1:
    print ('100 is less than 1')

if 2 == 2:
    print ('Two is equal to two')
    print ('Remember to use double equal signs')

if 'Julie' == 'Julie':
    print ('We can also compare strings using the double equal sign')
```

Output:
```
Two is equal to two
Remember to use double equal signs
We can also compare strings using the double equal sign
```

Note that only the code from the second two if statements prints.  This is because those two if statements contain true conditions while the condition of the first if statement is false.  This means that the code under the if statement does not run.

Also note that multiple lines of code can be under an if statement, as long as all of the lines are indented.


## Copyright Notice
Python Tutorial: If Statements
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

