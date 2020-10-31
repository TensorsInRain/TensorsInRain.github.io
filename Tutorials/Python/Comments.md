# Python Tutorial: Comments

[Home](../../README.md) -- [Tutorials](../../Tutorials/README.md) -- [Blog](../../Blog/README.md) -- [About Me](../../aboutme.md) -- [Contact](../../contactme.md) -- [Resume](../../Resume.pdf) -- [Copyright](../../copyright.md)

March 17, 2020

Go through this tutorial interactively on [Colab](https://colab.research.google.com/drive/1Alsds2fmKqg98P1yCHRi7I7ONnsyfSDC).  Once you follow the link click "Open in Playground Mode" (this does not save your work) or download as an ".ipynb" file and upload it to your own Google Drive if you want to keep your progress.

## Introduction to Comments

A *comment* is a line in the code that Python ignores.  You can make a comment by adding a `#` to the beginning of a line.

For example, in the following two lines of code, both `Robot` and `Code` will be printed.

``` python
print('Robot')

print('Code')
```

Output:
```
Robot
Code
```

However, if I comment out the second line with a `#` then only `Robot` will print.

``` python
print('Robot')

#print('Code')
```

Output:
```
Code
```

Comments are usually used to explain what your code does.  This is useful if someone else needs to look at your code, or when you come back to your code after not looking at it for awhile.

For example, if I have the following code:

``` python
print('Julie')

print(24)
```

Output:
```
Julie
24
```

I could add these comments to it to make the code make more sense when someone else is reading it.

``` python
# Displays my name
print ('Julie')

#Displays my age
print(24)
```

Output:
```
Julie
24
```


## Copyright Notice
Python Tutorial: Comments
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
