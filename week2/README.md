# CS97 Discussion, Week 2
## Function
### Function practice: #1

Remember quadratic equations? They take the form a{x}^{2} + bx + c = y. Write a function that takes four arguments and returns y.

### Function practice: #1-2

Now, use the function you just wrote, and write a function that takes values for a, b, c, and x and tells you whether or not "x" is a solution to that equation. Remember that a solution to a quadratic equation is a value for x that makes the whole thing equal to 0.



## Recursion
### Recursion practice #0
From the lecture: Given a list of integers, e.g. [3, -1, 2, 0, 7, -5], return the list modified so that it contains only positive (>= 1) integers.

### Recursion practice #1
Read the following code. What does it do? How many times is this function called, and with what arguments? Hint: try expanding the last statement with each new function call!

```python
# assume n > 0
def foo(n):
	if n == 1:
		return 1
	elif n == 2:
		return 1
	else:
		return foo(n - 1) + foo(n - 2)
>> foo(4)

```


### Recursion practice #1-2
What does this function return when x=36 and y=12? Can you come with a general description of what it does?
```python
def mystery(x, y)
	if x < y:
		return mystery(x, y-x)
	elif y < x:
		return mystery(x-y, x):
	else:
		return x
```


### Recursion practice #2

Write code to reverse a list, making sure you use recursion in a useful way.
```
>>> revList([1,2,3,4])
[4, 3, 2, 1]
```

### Recursion practice #2-2, stretch question
If you finish that early, try using the function you wrote to write another function that takes in a list of characters and returns True if the list of strings represents a palindrome.
A palindrome is a sequence of letters like "racecar" where it's the same when reversed :) It should work for either strings or lists



