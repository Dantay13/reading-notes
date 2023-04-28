# Class 3 Reading: FileIO & Exceptions

## Reading

- [Read & Write Files in Python](https://realpython.com/read-write-files-python/)
- [Exceptions in Python](https://realpython.com/python-exceptions/)

## Video

- [File Objects - Reading and Writing to Files](https://www.youtube.com/watch?v=Uh2ebFW8OYM)

## Bookmark

- [Reading and Writing Files in Python Quiz](https://realpython.com/quizzes/read-write-files-python/)

## Reading Questions

1. What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?

    The 'with' statement in Python is a helpful tool that automatically takes care of managing files (or other resources). When you use the 'with' statement to open a file, Python will automatically close it for you when you're done with it. This helps prevent problems like losing data or making mistakes in your code. By using the 'with' statement, you can make your code simpler, easier to read, and less likely to have errors.

2. Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.

    The 'read()' method reads the entire file contents as a string, while 'readline()' reads one line at a time. Use 'read()' to read the whole file into memory, and 'readline()' to process the file line by line.

3. Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.

    Exception handling is a way to deal with errors in Python. We use 'try', 'except', and 'finally' blocks to handle exceptions. 'Try' is where we put the code that might cause an error. 'Except' is where we put the code that will run if an error happens. 'Finally' is where we put code that will always run.
