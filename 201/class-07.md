# Class 07 Readings: Object-Oriented Programming, HTML Tables

## Domain Modeling

- Explain why we need domain modeling.
<br> Domain modeling allow not only technoical people to understand the problem being solved but also to provide clarity to other stakeholders.

## HTML Table Basics

- Why should tables not be used for page layouts?

1. Layout tables reduce accessibility for visually impaired users
2. Tables have a more complex markup structure than page layouts which can result in the code being harder to write, maintain, and debug.
3. Tables are not automatically responsive like proper page layout containers.

- List and describe 3 different semantic HTML elements used in an HTML

1. `<th>` (Table Header): This is the header at the begining of the table used to describe the type of data that will follow.
2. `<tr>` (Table Row): This tag is the table row, which provide a cell to describe the data that will be in that row.
3. `<td>` (Table Data): This tag house the data.

## Introducing Constructors

- What is a constructor and what are some advantages to using it?
<br> A constructor is a function created to manufactor objects without having to code in different object literal.

### Advatages

1. Cleaner code that improve readability
2. Allows you to dynamicaaly create objects in one line of code

- How does the term `this` differ when used in an object literal versus when used in a constructor?
<br> The `this` keyword when used in a on=bject literal is refering to the same object the mothod is located in, meaning that the result would be the same is the only the object name was used. In the sense of a object constructor, the keyword `this` would become more useful because it refer to a specific object out of multiple.

## Object Prototypes Using A Constructor

- Explain prototypes and inheritance via an analogy from your previous work experience.

## Things I want to know more about

I would like to know more about how to properly use prototypes and better understand the fundamental of it.

[<== BACK](README.md)
