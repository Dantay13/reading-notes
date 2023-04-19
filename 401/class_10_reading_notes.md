# Class 10 Read: Stacks & Queues

## [Stacks and Queues](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/stacks_and_queues.html)

### Stack

It is a linear data structure that consist of nodes referencing to the next node in the stack, but does not reference the previous node. a stack can be visualized as a stack of plates.

Key Features:

 1. A stack has a top, which is the last node `push` to the stack and will be the first to get `pop` from the stack
 2. a stack follows a LIFO concept, which means last in first out.
 3. a node is added to a stack by using the `push` function
 4. a node is removed from a stack by using the 'pop' function
 5. `peek()` is used to view the value of the top node in the stack
 `isEmpty` returns a boolean if the stack is empty or not

 ![stack image](img/stack1.png)

### Queue

is also a linear data structure, with nodes. It is very similar but differ by a a few features. A queue can be visualized as a line to enter a movie theater.

key Features:

1. a queue follows a FIFO concept, which mean first in first out.
2. to add a node to a queue the term used is `Enqueue`
3. to remove a node from a queue the term used is `Dequeue`
4. a queue is comprised of a front, which is the first node of the queue and a rear/tail which is the last node of the queue
5. whe use the function `peek()` it will return the value of the front node in the queue
`isEmpty` returns a boolean if the queue is empty or not

![queue image](img/Queue.png)

