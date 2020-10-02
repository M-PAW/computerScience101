
# Nodes

 - A locational object that references other objects.

 - Nodes contain the following: Previous and Next.
    - Each points to what the name implies.

 - It allows you to link data / a program together regardless of the location. Imagine a fragmented
   harddrive, with a larger program it will try to fill available slots with what it can, a little
   here and a little there, and each of these will point to the next location to be read. This behavior
   is less common with solid state drives, think in terms of mechanical harddrives.


# Singly Linked List

 - There is no return path as you can only travel in one direction,
   which means that with each traversal you need to begin again at
   the beginning. Only has a next pointer.

 - As you add a new node, the null value at the end of the list will be 
   placed in the next of the new node added at the end.

 - When removing a node, you need to link the adjacent nodes to repair
   the chain.

 - When inserting a node between two others, you need to redirect
   the pointers to maintain the links, if A -> C, then A -> B -> C
   after B is added.


## Singly Linked List Run-Times 

- Insert random is a worst case of o(n) - linear time
- Insert front is a worst case of o(1) - constant time
- Insert back is a worst case of o(n) - linear time
- Delete random is a worst case of o(n) - linear time
- Delete back is a worst case of o(n) - linear time
- Delete front is a worst case of o(1) - constant time
- Search sorted is a worst case of o(n) - linear time
- Search unsorted is a worst case of o(n) - linear time


# Doubly Linked List

 - Included a Previous pointer and a Next pointer.
 - While finding and deleting a value within a singly linked list requires
   that you traverse the list twice and often has a run time of
   o(2n), a doubly linked list only requires on traversal and has a run-time
   of o(n). While it isn't the most optimal, it's still a great improvement.

 - When deleting a node within a double linked list, we first traverse to find our node,
   then step back to the previos node, and set the next.next as our next address. Then we step
   forward to the new next node and repace its previos with the previous.previos pointer. Or while 
   on that node, we capture the previous and the next, and set them both to bypass that node at the same time,
   previous = previous.previous and next = next.next .


# Linked List - Tail Pointer

 - Can improve the run-time of your function / method. This often used in conjunction with a start pointer,
   so in turn you have a start pointer and a tail pointer. The tail pointer allows you to insert a new node into
   the back in Constant Time o(1) instead of Linear Time o(n).

