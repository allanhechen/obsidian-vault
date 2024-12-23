```python
list = [4, 3, 2, 1]

newList = sorted(myList)

list.sort()
```

- both functions sort in ascending order by default

- `sorted` is a function that returns a new list from the given list
- `list.sort()` sorts the function in-place and is slightly more efficient than sorted

- `sorted` works on any iterable

## key
- both have an optional input function `key` that is called before comparison of every element
- key takes a single element and returns a key for sorting purposes
- both functions call key once on every element and is thus fast
- usually items with complex attributes use keys to sort them
	- Class objects
	- named tuples
	- dataclasses