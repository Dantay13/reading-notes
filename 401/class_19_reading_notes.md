# Class 19

## Reading

- [Python Regular Expressions Tutorial](https://www.datacamp.com/community/tutorials/python-regular-expression-tutorial)
- [shutil](https://pymotw.com/3/shutil/)

## Additional Resources

- [Automation Ideas](https://www.youtube.com/watch?v=qbW6FRbaSl0&t=69s)
- [Optional: Automating Your Browser and Desktop Apps](https://www.youtube.com/watch?v=dZLyfbSQPXI)

# Bookmark and Review

- [Watchdog](https://pythonhosted.org/watchdog/)

## Reading Questions

1. How can you use regular expressions in Python to search for specific patterns in a string, and what is the primary library to work with them?

    Regular expressions in Python are used to search for specific patterns within a string of text. The primary library for working with regular expressions in Python is called re.

2. What is the purpose of the shutil library in Python, and provide an example of a common use case for file or directory management with this library?

    The shutil library in Python serves the purpose of simplifying file and directory management tasks. It provides functions to copy, move, rename, and delete files and directories.

    A common use case for the shutil library is when you need to create a backup of a directory. For instance, if you have a directory called "source" with important files, you can use shutil.copytree() to easily create a backup of that directory by copying all its contents to a new directory named "backup".

3. Explain one automation idea from the assigned material and describe how it can be implemented using Python’s regular expressions and shutil libraries.

- Automatically moving files