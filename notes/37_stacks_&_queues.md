
# Stacks & Queues
 - I dediced to join these two sections into one notes file.


## Stack - LIFO
 - A stack follows the directive of first in last out,
   meaning that once a piece of data, data"A", and then 
   another piece of data is placed ontop of it, data"B",
   data"A" cannot be removed until data"B" has been removed.
   Items are removed in reverse order.
 
 - The methods commonly used for manipulating this data
   are push() and pop().

 - Data is returned in reverse order of how it was pushed.


## Queue - FIFO
 - A queue follows the directive of first in first out,
   meaning that once a piece of data, data"A" and then 
   another piece of data is placed ontop of it, data"B",
   data"A" will be removed from the bottom - before data"B"
   will be removed.

 - The methods commonly used for manipulating this data
   are enqueue and dequeue

 - Data is returned in the same order as it was pushed, and
   the queue moves down as each item is taken out.


## Run-times of Stacks and Queues

 - They are dependent on what type of data structure they are built upon.

 - Our goal is to make each operation equal to o(1) - Constant Time.
   ### This can be done with an array as long as it has an end/tail pointer.
   ### This can also be done with a linked list as long as it has both 
   ### a head pointer and a tail pointer.

  

