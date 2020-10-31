# Python Tutorial: Lists

March 21, 2020

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

