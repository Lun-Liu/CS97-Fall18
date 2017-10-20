# CS97 Discussion, Week 3
## LA survey:

Please take this survey for our learning assistants [here](http://bit.ly/2ipoQfr )

## Debugging
This function is supposed to return the sum of all of the even numbers in a list, but it has a lot of bugs. Find them!

```python
def sumEvens(lst):
	if lst = []:  	
		return [] 
	elif lst[0] % 2 == 0    	
		return l[0] + sumEvens(lst)  
	else lst[0] % 2 != 0:
		return sumEven(lst) 
```

## Warm up coding practice

Remember the "pow" function? It takes two numbers, n and m and returns n^m. (In Python, you can also use the ** operator to achieve this effect!) Implement the pow function; your version is dumber than the library version  and won't work if m is not a nonnegative integer. 

## Code reading
```python
def mystery(str1, str2):
	if len(str1) != len(str2) or len(str1) < 1:	
		return ""
	if len(str1) == 1:	
		return str1[0] + str2[0]
	return str1[0] + str2[0] + mystery(str1[1:], str2[1:])
>> mystery("sok", "poy")
```

How many times is it called? With what? Final output? General description?

## Helper Function
Sometimes, recursive problems can only be solved (or can be solved more easily) by using an extra function that does all the extra work.

Please complete this function
```python
def index(l): 
	"""   Convert a list into an indexed list:
	>>>   index(["i", "a", "m", "a"])
	[["i", 0], ["a", 1], ["m", 2], ["a", 3]]
	"""
```

## zip and unzip
Complete the ```zip``` and ```unzip``` functions

```python
def zip(l1, l2):
	"""
	l1, l2 are two lists of same length
	Returns a zipped list
	>>> zip([1,2,3], ["one", "two", "three"])
	[[1,"one"], [2, "two"], [3, "three"]]
	>>> zip([], [])
	[]
	>>> zip([1], [11])
	[[1, 11]]
	"""
```

```python
def unzip(l):
	"""
	l is zipped list
	Returns a list of two unzipped lists

	>>> unzip([[1,"one"], [2, "two"], [3, "three"]])
	[[1,2,3], ["one", "two", "three"]]
	>>> unzip([])
	[[], []]
	>>> unzip([[1, 11]])
	[[1], [11]]
	"""
```

## countDigits

Please complete the function below that counts how many digits are there in a number

```python
def countDigits(n):
	"""
	return number digits in a number. Assume n is a positive integer. Hint: play with / and % in IDLE!"""
	>>> countDigits(9)
	1
	>>> countDigits(12345)
	5
	>>> countDigits(320190)
	6
	"""

```

