# Class 8 Readings: Ten Thousand 3

## Reading

- [List Comprehensions](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)

## Audio

- [Listen (optional): Debugging with PySnooper](https://www.pythonpodcast.com/pysnooper-python-debugging-episode-241/)

## Bookmark

- [Primer on Decorators](https://realpython.com/primer-on-python-decorators/)

## Questions

1. What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers.

the basic syntax of list comprehension is similar to the syntax to express a regular list, but it have three (3) important aspect to take into consideration.

- the expression inside the square bracket: this is the expression that will be acrried out
- the item inside the square bracket: this is the object that the expression will work on
- the list inside the square bracket: this is the iterable list of objects to build out the new list from

```py
squares = [x**2 for x in range(10)]
        
print(squares)

output = [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
```

2. What is a decorator in Python?

3. Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading.
