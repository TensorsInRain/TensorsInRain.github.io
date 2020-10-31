# Python Tutorial: While Loops

March 21, 2020

Many times while coding you will want to repeat a piece of code many times, one right after the other.  One way of doing this in Python is known as a while loop.  A while loop has a very similar structure to an if statement, but they run differently.  This is the structure of a while loop.  IT contains a key word (`while` instead of `if`), a condition followed by a colon, and some code under the while statement that is **indented**.

```
while condition:
    # This code runs as long as the condition is true
    Some code
```

With an if statement, if the condition is true then the code under the if statement runs exactly one time before the code moves onto the next part.  With a while loop as long as the condition is true the code under the while statement will continue to run.

Below is an example that illustrates how a while loop will continue to run until its condition is made false.

``` python
# Initialize the value of a
a = 0

# The loop will only run if the value stored in a is less than 10
while a < 10:
    # Print the current value of a
    print ('The while loop is running!  The value of a is', a)
    # Add one to the current value of a
    a += 1
```

Output:
```
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 1
The while loop is running!  The value of a is 2
The while loop is running!  The value of a is 3
The while loop is running!  The value of a is 4
The while loop is running!  The value of a is 5
The while loop is running!  The value of a is 6
The while loop is running!  The value of a is 7
The while loop is running!  The value of a is 8
The while loop is running!  The value of a is 9
```

The value of a is initialized to be zero before the while loop starts running.  Next, the condition of the while loop is checked with a = 0.  Since 0 < 10, the while loop condition is true so the code under the while loop runs.  First the print statement displays to the console the current value of a, and then a is incremented by 1 using an assignement operator.  This means that now a = 1.  After both of these lines run, the code goes back to the condition of the while loop and checks with the new value of a.  The condition is still true (1 < 10) so the code under the while loop runs again.  This continues until a=9.  When a=9 the condition is still true (9 < 10), so the code under the while loop runs.  The second line of code uner the while loop increments the value of a to 10, so when the while loop condition is checked again, it is false because 10 is not less than 10.  This means that the while loop will stop running and the Python program will move onto whatever is next.

If we wrote the same code, but removed the assingment operator from under the while loop then a will always be zero.  This means that the condition of the while loop will always be true, so the code under the while statement will always run.  This is called an _infinite loop_ and is something you will always want to avoid in programming because it causes your code to _hang_, or to not move forward because it is stuck on the loop.  

``` python
a = 0

while a < 10:
    print ('The while loop is running!  The value of a is', a)
```

Output:
```
...
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
The while loop is running!  The value of a is 0
...
```

While loops have many uses in programming.  One common use of while loops is to perform a mathematical operation on some numbers.  For example the code below finds the sum of all numbers between 1 and 100, including 1 and 100.  It then prints the total sum.

``` python
# Initialize the value of sum to be zero
# This variable will hold the sum of all the numbers
# from 1 to 100
sum = 0

# Initialize a to be 1.  a will run from 1 to 100 using 
# a while loop
a = 1

# This loop will run while a is less than 101, meaning that
# the largest value that will make the while loop run is 100.
while a < 101:
    # Add the current value of a to the sum variable
    sum += a
    # Increase a by 1
    a += 1

# Print the total sum
print ('The sum of all numbers between 1 and 100 is', sum)
```

We will see while loops more as we move forward in more advanced topics in Python.
