
# Heaps

 - In essence a sub-tree with additional properites, the heap property.

 - Greater heap and Lesser heap

    - Greater heap, the root / parent will be greater than its children.
      Continuing down the tree.

    - The children must be less than the parent, and then will be sorted into
      the normal left and right. We want the tree to become a filled tree, and
      follow a specific pattern. Left to right, not specific on high to low.

    - When a larger number is about to violate our Heap structure by being bigger than
      its parent, then we swap the number with the parent, then perform a recursive check
      that will check to see if the new parent is smaller or larger than the new parent.

    # Methods for Heaps
    
    - Insert: run-time 0(log n)
    - CheckMax: run-time 0(1)
    - RemoveMax: run-time 0(log n) as we are only dealing with the height of the tree.
        - After removing the head(max) we swap the bottom node to it, and
          then use recursion to move everything to its proper place.
    - GetMin: run-time 0(1)

# Djikstras Algorithm uses a heap.
 - It works off of finding the shortest path between beginning and end.    