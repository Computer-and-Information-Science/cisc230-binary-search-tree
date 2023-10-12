# Tree Traversals  

A *tree traversal* is the process of "visiting" each node of a tree in some particular order. For a binary search tree, we can talk about an *inorder traversal* and a *preorder traversal*. For this assignment you are to implement both of these traversals in the code that was started in class.

File *bstree.h* contains the *BSTree* class that was developed during class (with the addition of comments which were omitted by your instructor due to time constraints). The class contains two *inorder* functions, one public and one private, and two *preorder* functions, also one public and one private. As was the case with other functions implemented for this class, the public versions of these functions simply call the private versions passing the root node (pointer) as a parameter. The private versions carry out their actions on the subtree rooted at the given node.

The code provided in *bstree.h* is missing the implementations for the private *inorder* and *preorder* functions. The coding part of this assignment is to implement these two functions.

When completed, the test program provided should produce the following output:

```
Values stored in the tree are:
bird
cat
deer
dog
giraffe
groundhog
horse
snake
turtle

The structure of the tree is as follows:
dog
-bird
--cat
---deer
-turtle
--giraffe
---snake
----groundhog
-----horse
```

## Written Part

In addition to the coding noted above, give an analysis of all public member functions of the class, including all constructors, the destructor, and the overload of the assignment operator. For your analysis you may assume a well-balanced tree (whereas a lopsided tree might lead to a different analysis).