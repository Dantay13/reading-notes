# Class 42 Readings: Pythonisms

## Reading

[Dunder Methods](https://dbader.org/blog/python-dunder-methods)
[Iterators](https://dbader.org/blog/python-iterators)
[Generators](https://dbader.org/blog/python-generators)

## videos

[What are Generators](https://realpython.com/lessons/what-are-python-generators/)

## Bookmark and Review

[Decorators](https://realpython.com/primer-on-python-decorators/)

## Reading Questions

1. What are dunder methods in Python, and how do they allow for the customization of built-in behavior in classes? Provide an example of a common dunder method and its purpose.

    Dunder methods, or "double under" methods, are special methods in Python that allow customization of built-in behavior in classes. Recognized by double underscores at the beginning and end of their names, such as __init__ or __str__, they enable the emulation of built-in types, object representation, operator overloading, iteration, and more. For example, the __len__ method can be used to define how the len() function behaves with a custom class. These methods make classes more expressive and Pythonic, allowing developers to interface with rich language features and write more maintainable code.

2. Explain the concept of an iterator in Python. How do you create a custom iterator using the iter() and next() methods, and why are they important for enabling iteration in a class?

    An iterator in Python is an object that allows for the sequential traversal of a container, such as a list or tuple. It must implement two methods, __iter__() and __next__(), to be considered an iterator. The __iter__ method returns the iterator object itself, while the __next__ method returns the next value from the iterator, raising a StopIteration exception when there are no more items. This concept enables memory-efficient iteration over large datasets and provides a uniform interface for iterating over different types of objects, allowing for custom behavior and integration with for-in loops.

3. What is a generator in Python, and how does it differ from a regular function? Illustrate your answer with an example of a generator function using the ‘yield’ keyword.

    A generator in Python is a special type of function that allows you to write iterators with less code and in a more readable way. Unlike regular functions that return a value and exit, generators use the yield keyword to pass data back to the caller and temporarily suspend execution, retaining their local state.

    ```py
    def repeater(value):
    while True:
        yield value
    ```
