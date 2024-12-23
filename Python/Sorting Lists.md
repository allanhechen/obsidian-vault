```python
list = [4, 3, 2, 1]

newList = sorted(myList)

list.sort()
```

- `sorted` is a function that returns a new list from the given list
- `list.sort()` sorts the function in-place and is slightly more efficient than sorted

- `sorted` works on any iterable, while `list.sort()` only works on lists

- both methods are "stable," which means that if they have the same key, their output order will match the original output order
	- this allows sorting to be done in multiple stages (ex. birthdays and then grades since many people will be in the same grade)

## key Argument
- both have an optional input function `key` that is called before comparison of every element
- key takes a single element and returns a key for sorting purposes
- both functions call key once on every element and is thus fast
- usually items with complex attributes use keys to sort them
	- Class objects
	- named tuples
	- dataclasses

## Sorting Order
- both sort in ascending order by default
- the `reverse=True` argument can be provided for sorting in descending order