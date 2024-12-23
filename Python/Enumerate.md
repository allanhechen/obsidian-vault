```python
for (index, item) in enumerate(iterable, start=0):
	# do something with the returned value
```

Functionally equivalent to the following, but doesn't return as a string
```python
def enumerate(iterable, start=0):
	result = []

	for i in iterable:
		result.append((start, i))
		start += 1

	return result
```

- Takes in an iterable object and pairs it with some numbers

What does the "start" variable represent in enumerate?
___
It represents the first number it pairs with the iterable object.
<!--SR:!2024-12-25,3,250-->

#flashcards/python