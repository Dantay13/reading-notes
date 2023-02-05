# Class 9 Readings: Functional Programming

## [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

1. What is functional programming?
<br> Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
2. What is a pure function and how do we know if something is a pure function?
<br> A pure function returns the same result if given the same arghuments and it does not cause any observable side effects.
3. What are the benefits of a pure function?
<br> - The code is easier to test
<br> - No need to mock anything, as the result shoukd be as expected.

4. What is immutability?
<br> Unchanging over time or unable to be changed.
5. What is Referential transparency?
<br>If a function consistently yields the same result for the same input, it is referentially transparent.
<br>**pure functions + immutable data = referential transparency**

## [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

1. What is a module?
<br> A module is a javascript file
2. What does the word ‘require’ do?
<br> It specify the module we want to use in the current module we are located in.
3. How do we bring another module into the file the we are working in?
<br> We must export the module.
4. What do we have to do to make a module available?
<br> We must first require the module into the file we are working in and export the specific method of that module to be able to can use it.
