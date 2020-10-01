
# Fixed Array Run-Times

## Insert (Random) - Linear Time
 - To insert a random to the front of the array, the average run-time will
   be something close to O(n)

## Insert (Front) - Linear Time
 - Insertion to the front will be O(n) because we need to move all of the
   values down by one.

## Insert (Back) - Constant Time
 - Insertion to the back uses constant time of O(1), as nothing needs to be changed
   or moved.

## Delete (Front) - Linear Time
 - When we delete an item from the front, we also need to move all of the remaining items
   to the left so that the array once again begins at 0.
 - The time complexity is O(n).

## Delete (Back) - Constant Time
 - This, much like insertion, has no need to adapt or change the array after removing an item.
   The most that may need to happen is a decrease in the declared size.

- The time complexity is that on O(1)

## Search (Unsorted) - Linear Time

 - In an unsorted array, it becomes essential to go through all  of the values
   one by one while searching for your target.

 - It has a best and worst case, but on average it is O(n).

## Search (Sorted)

 - As this data set is sorted, and in a particular order, it is possible to
   search by using mid-points to hunt for a target value. Which in essence lowers the 
   time required to a fractional amount. The access time is greatly reduced.

 - Time complexity of O(logn), when using a binary search algorithm on a sorted data set.

 - When going through a data set, per each step taken while using a binary search,
   the data is cut in half. Instead of taking 128 steps to find our target, we would
   only need 7(Sometimes 6, depending on how you write your checks).
    - EG:  Original data set size of 128
        1. Step 1: 64
        2. Step 2: 32
        3. Step 3: 16
        4. Step 4: 8
        5. Step 5: 4
        6. Step 6: 2
        7. Step 7: 1 - We found the target

 - This algorithm patterns has a run-time of log(n)
