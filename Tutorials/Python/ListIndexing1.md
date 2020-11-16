# Python Tutorial: Forward List Indexing

[Home](../../README.md) -- [Tutorials](../../Tutorials/README.md) -- [Blog](../../Blog/README.md) -- [About Me](../../aboutme.md) -- [Contact](../../contactme.md) -- [Resume](../../Resume.pdf) -- [Copyright](../../copyright.md)

November 16, 2020


In the section above you learned how to show the entire contents of a list using a print statement, but what if you only want to print one element of the list?  Python has a way to do this and its called list indexing.

First, lets create a list to work with and then print its contents.

``` python
# Creating a list and then printing the contents
animals = ['dog', 'cat', 'cow', 'pig', 'horse']
print(animals)
```

Output:
```
['dog', 'cat', 'cow', 'pig', 'horse']
```

If I just put the name of the list in the print statement it prints the entire lists.  If I want to print just the first element I can use list indexing.

``` python
print(animals[0])
```

Output:
```
dog
```

The above statement prints just the first element in the `animals` list.  The square brackets after the list's name tells Python that I am going to be using list indexing and the number inside of the square brackets tells Python which element I want.  The first element in a list is always index 0, the second element is index 1, and so on.  I can print out each element of the list individually using the following code:

``` python
print(animals[0])
print(animals[1])
print(animals[2])
print(animals[3])
print(animals[4])
```

Output:
```
dog
cat
cow
pig
horse
```

The list `animals` has five elements in it.  This means that the first element is at index 0 and the last element is at index 4 (one less than the length of the list).

I can also use indexing to set elements in the list equal to variables.  For example if I know that the element at index 2 of the list is my favorite animal then I can write the following code:

``` python
my_favorite_animal = animals[2]
print(my_favorite_animal)
```

Output:
```
cow
```

## Copyright Notice

Python Tutorial: Forward List Indexing

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
