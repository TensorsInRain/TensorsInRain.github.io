# Python Tutorial: Changing the Value of a Variable using Assignment Operators

March 21, 2020

Lets say we have a variable that is equal to a number, but we want to change that variable by doing some type of math to it.  Using the skills you currently have, here is how you would do it.

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
Python offers a cleaner way of doing the exact same thing using _assignment operators_.  If I want to add a number to an already existing variable I can use the addition assignement operator:

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
