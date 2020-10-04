
# Stable vs Nonstable
 - Whether an algorithm is stable or nonstable.

 - Case (duplicate values):
    - if a number is duplicated in an array, it may become unstable and the 
      order for sorting may behave unpredictably.

 - Two of the sorting algorithms that lack in terms of stability are:
    - Selection Sort Case:
        - If we have three values in an array [2a,2b,1],
          and we sort the array using selection sort,
          we have no guarantee that the first 2 in the array will be placed
          in the correct position. Which if this algorithm were used for
          a public queueing system in which people had to wait, it would cause error,
          contention, and anger.

    - Quick Sort Case:
        - What if we have an array [2a,2b,1], if we chose 2a as our pivot.
          when sorting the 1 would be placed to the front in the left array,
          and 2b is placed into the array at the right. When they are recombined the 
          2a and the 2b would have changed places and not be in the correct order.