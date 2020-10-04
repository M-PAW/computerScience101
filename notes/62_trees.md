
# Trees
 - A data structure containing a root node, and branching out in an exponential
   fashion until all of the values are assigned to their own nodes.
 
 - The structure of a node looks similar to this:
    data | parent node | left pointer | right pointer

 - The average run-time when working with a tree is log(n).


# Binary Search Tree - BST
 - A data structure that contains a root node, and branches out
   in two directions. With a left and a right, the left is for less
   than the current node value, and right is for numbers greater than
   node value. This branching continues until all of the values are
   assimilated into the BST.

 - The nodes below the root are called children, and each generation
   of children are classified into level / iterations / steps.

 - The average run-time is log(n), an inverse exponential equations.

# BST run-times
 operation   |   Average   |   Worst Case
 Search          o(log n)       o(n)
 Insert          o(log n)       o(n)
 Delete          o(log n)       o(n)


# Things to Lookup
 1. AVL
 2. Red Black Tree



# Tree Traversals
 - In order: Left, Root, Right
    - Goes down the target sub-tree, taking the left if available, if not then go right.
      Treating each nodes passed as a root, and collecting it last as it returns to the
      root at the top before collecting it and then moving to the right side of the tree.
      The data returned should be in either ascending or descending order.

 - Pre-order: Root, Left, Right
    - Grab the root, then explore the left sub-tree, then left, then the right.

 - Post-order: Left, Right, Root
    - Explore the left sub-tree first, then right, then grab the main root.
