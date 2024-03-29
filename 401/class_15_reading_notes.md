# Class 15 Reading Implementation: Trees

## [Trees](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)

### Common Tree Terminology

- Node - A Tree node is a component which may contain its own values, and references to other nodes
- Root - The root is the node at the beginning of the tree
- K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, `k = 2`.
- Left - A reference to one child node, in a binary tree
- Right - A reference to the other child node, in a binary tree
- Edge - The edge in a tree is the link between a parent and child node
- Leaf - A leaf is a node that does not have any children
- Height - The height of a tree is the number of edges from the root to the furthest leaf

Sample tree

![binary tree](img/BinaryTree1.png)

- Traversing:
Traversing, in a general sense, refers to the act of moving through or crossing a particular path or structure. In the context of computer programming and data structures, traversing refers to the process of visiting and examining each element or node of a data structure in a specific order.

#### Depth First Traversing

Depth first traversal is where we prioritize going through the depth (height) of the tree first.

- Pre-order: `root >> left >> right`
- In-order: `left >> root >> right`
- Post-order: `left >> right >> root`

![tree traversing example](img/tree-example.png)

- Pre-order: `A, B, D, E, C, F` (TOP DOWN)
- In-order: `D, B, E, A, F, C` (LEFT TO RIGHT)
- Post-order: `D, E, B, F, C, A` (BOTTOM UP)

#### Traversal Pseudocode

Pre-order -->

```py
ALGORITHM preOrder(root)
// INPUT <-- root node
// OUTPUT <-- pre-order output of tree node's values

    OUTPUT <-- root.value

    if root.left is not Null
        preOrder(root.left)

    if root.right is not NULL
        preOrder(root.right)
```

In-order

```py
ALGORITHM inOrder(root)
// INPUT <-- root node
// OUTPUT <-- in-order output of tree node's values

    if root.left is not NULL
        inOrder(root.left)

    OUTPUT <-- root.value

    if root.right is not NULL
        inOrder(root.right)
```

Post-order

```py
ALGORITHM postOrder(root)
// INPUT <-- root node
// OUTPUT <-- post-order output of tree node's values

    if root.left is not NULL
        postOrder(root.left)

    if root.right is not NULL
        postOrder(root.right)

    OUTPUT <-- root.value
```

### [VISUALIZATION OF BINARY TREE TRAVERSAL](https://www.issacc.com/binary-tree-traversal-preorder-inorder-postorder/)
