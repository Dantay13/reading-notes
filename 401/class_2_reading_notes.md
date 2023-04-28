# Class 2 Reading: Testing and Modules

## Reading

- [In Tests We Trust - TDD with Python](https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)
- [If name equals main](https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/)
- [Recursion](https://www.geeksforgeeks.org/recursion/)

Videeos

- [What on Earth is Recursion](https://www.youtube.com/watch?v=Mv9NEXX1VHc)
- [Python Modules and Packages Companion Video](https://realpython.com/courses/python-modules-packages/)

## Bookmarks

- [Google for Education: Python Lists](https://developers.google.com/edu/python/lists)
- [Google for Education: Python Strings](https://developers.google.com/edu/python/strings)
- [Python Modules and Packages](https://realpython.com/python-modules-packages/)
- [Pytest Documentation](https://docs.pytest.org/en/latest/)
- [PyTest Tutorial](https://www.guru99.com/pytest-tutorial.html)

## Reading Questions

1. What are the key principles of Test-Driven Development (TDD) in Python, and how do they contribute to the overall quality of code?

    - Unit test - pieces of code to exercise the input, the output and the behaviour of your code.
    - TDD - a strategy to think (and write!) tests first.


2. Explain the purpose of the if __name__ == '__main__': statement in Python scripts. What are some use cases for including this conditional in your code?

    Advantages :

    - Every Python module has it’s __name__ defined and if this is ‘__main__’, it implies that the module is being run standalone by the user and we can do corresponding appropriate actions.
    - If you import this script as a module in another script, the __name__ is set to the name of the script/module.
    - Python files can act as either reusable modules, or as standalone programs.
    - if __name__ == “main”: is used to execute some code only if the file was run directly, and not imported.

3. Describe the concept of recursion in Python.

        "A recursive function (in python) solves a particular problem by calling a copy of itself and solving smaller subproblems of the original problems."

4. What is the difference between Python modules and packages? Explain how to create, import, and use them in your Python programs.

        A module is a single file containing Python code. It can contain functions, classes, and variables, which can be accessed by other Python programs using the import statement. A package is a collection of modules organized in a directory tree.
