# JavaScript Loops

Loops offer a quick and easy way to do something repeatedly.
<br> You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another.
<br> There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)
<br> The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.

[The different statements for loops provided in JavaScript can be found here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

## For Statement Loop

A `for` loop repeats until a specified condition evaluates to false.
<br> A for statement looks as follows:

![image 1](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/class8img1.png)

When a `for` loop executes, the following occurs:

1. The initializing expression `initialExpression`, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2. The `conditionExpression` expression is evaluated. If the value of `conditionExpression` is true, the loop statements execute. Otherwise, the `for` loop terminates. (If the `conditionExpression` expression is omitted entirely, the condition is assumed to be true.)
3. The `statement` executes. To execute multiple statements, use a [block statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/block) (`{ ... }`) to group those statements.
4. If present, the update expression `incrementExpression` is executed.
5. Control returns to Step 2.

[View `for` loop example here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

## While Statement

A `while` statement executes its statements as long as a specified condition evaluates to `true`. A while statement looks as follows:

![image 2](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/class8img2.png)

If the `condition` becomes `false`, `statement` within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before `statement` in the loop is executed. If the condition returns `true`, `statement` is executed and the `condition` is tested again. If the condition returns false, execution stops, and control is passed to the statement following `while`.

To execute multiple statements, use a block statement (`{ ... }`) to group those statements.

### While Loop Example 1

The following `while` loop iterates as long as `n` is less than `3`:

![image 3](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/class8img3.png)

With each iteration, the loop increments n and adds that value to x. Therefore, x and n take on the following values:

- After the first pass: `n` = `1` and `x` = `1`
- After the second pass: `n` = `2` and `x` = `3`
- After the third pass: `n` = `3` and `x` = `6`

After completing the third pass, the condition `n < 3` is no longer `true`, so the loop terminates.

### While Loop Example 2

Avoid infinite loops. Make sure the condition in a loop eventually becomes `false`—otherwise, the loop will never terminate! The statements in the following `while` loop execute forever because the condition never becomes `false`:

![image4](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/class8img4.png)

[Source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

## Expressions and Operators

### Assignment Operators

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (`=`), which assigns the value of its right operand to its left operand. That is, `x = f()` is an assignment expression that assigns the value of `f()` to `x`.

There are also compound assignment operators that are shorthand for the operations listed in the following table:

![image5](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/class8image5.png)

#### Assigning to Properties

If a variable refers to an [object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects), then the left-hand side of an assignment expression may make assignments to properties of that variable. For example:

![image6](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/class8image6.png)

#### Destructuring

For more complex assignments, the [destructuring assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment) syntax is a JavaScript expression that makes it possible to extract data from arrays or objects using a syntax that mirrors the construction of array and object literals.

![image7](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/class8image7.png)

[More about Assignment Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators)

### Comparison Operators

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or [object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects) values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the `===` and `!==` operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. The following table describes the comparison operators in terms of this sample code:

![image8](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/class8image8.png)

![image9](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/class8image9.png)

[Source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#comparison_operators)

[<==BACK](README.md)
