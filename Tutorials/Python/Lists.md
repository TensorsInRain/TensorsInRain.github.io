# Python Tutorial: Introduction to Lists

[Home](../../README.md) -- [Tutorials](../../Tutorials/README.md) -- [Blog](../../Blog/README.md) -- [About Me](../../aboutme.md) -- [Contact](../../contactme.md) -- [Resume](../../Resume.pdf) -- [Copyright](../../copyright.md)

November 16, 2020

Go through this tutorial interactively on [Colab](https://colab.research.google.com/drive/1gZ_7fUJP9H_Eh1W0bA9cYDjMLLWttqbF?usp=sharing).  Once you follow the link click "Open in Playground" (this does not save your work) or download as an ".ipynb" file and upload it to your own Google Drive if you want to keep your progress.

In Python a _list_ is a collection of variables or data that have been grouped together.  You can make a list in Python by surrounding your data with square brackets (`[]`) and separating each entry with a comma.  For example, if I wanted to make a list of programming languages, I could do the following:

``` python
programming_languages = ['Python', 'C++', 'Java', 'Fortran']
```

What I have done is create a list that contains four strings: `'Python'`, `'C++'`, `'Java'`, `'Fortran'`.  I have then assigned the list to be contained in the variable named `programming_languages` (see [this](VariablesAndPrint.md) tutorial for a review of variables).  I can print out the contents of my list using a print statement.

``` python
print (programming_languages)
```

Output:
```
['Python', 'C++', 'Java', 'Fortran']
```

You can also create an empty list which contains no objects.

``` python
# Create an empty list and then print the list to prove that it is empty
my_list = []

print(my_list)
```

Output:
```
[]
```

Empty lists are useful because you can always items to the list later using an `append` statement.  If I want to add a number to the empty list I created above, I can do the following:

``` python
# Print the current contents of my_list to prove that it is empty
print (my_list)
# Add the number for as an element in my_list
my_list.append(4)
# Show the new contents of my_list
print (my_list)
```

Output:
```
[]
[4]
```

List can contain variables, numbers, and strings in any combination and can be any length.  All of the below are valid examples of lists.

``` python
# An example of a list that contains only numbers
list_of_numbers = [3, 67, 53, 78]
# An example of a list that contains only strings
list_of_strings = ['dog', 'cat', 'cow', 'pig', 'horse']
# An example of a list created using variables
my_name = 'Julie'
my_age = 24
list_of_variables = [my_name, my_age]
# An example of a mixed list, containing numbers and strings
mixed_list = [34, 'cup', 587, 'plate']
```

## Copyright Notice

Python Tutorial: Introduction to Lists

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
