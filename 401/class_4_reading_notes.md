# Class 4 Reading

## [Classes and Objects](https://www.learnpython.org/en/Classes_and_Objects)-

- [Class and Object Tutorial](https://www.youtube.com/watch?v=8O5kX73OkIY)
- What are the key differences between classes and objects in Python, and how are they used to create and manage instances of a class?
  - A class in python is a template to create objects. Within that template we can variables and functions. An object is a entity with attributes made up of variables and functions.
- [Defining `__init__` & understanding `self`](https://www.youtube.com/watch?v=AjYOMk-4NIU)

## [Thinking Recursively](https://realpython.com/python-thinking-recursively/)

- NOTE
   - Iterative algorithm - occuring in a loop to repeat
   - Recursive algorithm - calling self to repeat

- [Recursion](https://www.youtube.com/watch?v=XkL3SUioNvo)
- [Recusion example: finding the factorial](https://www.youtube.com/watch?v=TqqQld6m6A0)

### Explain the concept of recursion and provide an example of how it can be used to solve a problem in Python. What are some best practices to follow when implementing a recursive function?

    Recussion is calling within itself, causing that function to repeat. By default a function will repeat itself 1,0000 times in Python.

### Recursive case & Base case

- Recursive case: Decompose the original problem into simpler instances of the same problem. This is the recursive case:
- Base case: As the large problem is broken down into successively less complex ones, those subproblems must eventually become so simple that they can be solved without further subdivision. This is the base case

### Best practices to follow in maintain state


![finding the factorial of 5 example of recursive case and base case](/Users/dannertaylor/Desktop/Screen Shot 2023-03-28 at 11.49.28 PM.png)



## [Pytest Fixtures and Coverage](https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage)

- What is the purpose of pytest fixtures and code coverage in testing Python code? Explain how they can be used together to improve the quality and maintainability of a project.

### Bookmarks

- [Pytest Fixtures](https://docs.pytest.org/en/latest/explanation/fixtures.html)