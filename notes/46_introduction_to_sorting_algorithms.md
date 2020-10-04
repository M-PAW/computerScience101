
# Introduction to Sorting Algorithms

- The benefit of having a sorted data set can make methods
  applied have their run time reduced to o(logn), which 
  is essentially o(1).


## Bubble Sort
 - This works in a linear fashion, often going from left to right,
   while swapping values if one is greater than the other,
   and placing them in an ascending order from left to right.
 - The biggest downside to this is the number of passes required
   to completely sort an array.
### The worst case run-time is o(n^2)
 

## Selection Sort
 - Starting from the left and going to the right, we grab the smallest value
   by comparing values as we move. Once we have the smallest value in the set
   we compare it the number in first position and determine if it goes before or 
   after the value. This continues until all is sorted.

 - The worst case run-time for this is o(n^2) - Linear Time


## Insertion Sort
 - Starting from the left and moving right, comparing values side-by-side
   and swapping the smaller value to the left. It works similarly to both
   selection sort and bubble sort. Once a value is selected, it will continue to compare until it reaches the point shere the number to the right of it is greater,
   and then inserts the value. Or even to the left being smaller.

- The worst case run-time for this is o(n^2) - Linear Time
- Best case if it's sorted, is o(n) - Constant Time


## Quick Sort
 - Works off of a pivot element, numbers less than and greater than the pivot will be 
   placed into separate sub-arrays, and this is repeated the sub-array isn't more than 
   one in length. In the end, after everything is broken down, it will be in an
   ascending order, and be reassenbled into a sorted array.

 - This essentially works in terms of exponential expansion, with the one off chance 
   of expanding too much.

 - The worst case run-time for this is n(log n) - Log Linear Time
 - This could be improved through the use of recursion.
 - If it hits the worst case scenario, your resources could become tied up
   and your computer may crash.


## Merge Sort
 - Takes a set of data and splits them equally into sub-arrays, this continues until they
   are individual values. Then we begin to recombine them, putting them in order as we go.
 
 - This is done by comparing the sub-arrays from the left most to the right most positions,
   and recombining them into a new array.

 - Once one array runs out of numbers to combine, we need to make it add in the rest of the remaining array.

 - The worst case run-time for this is n(log n) - Log Constant Time, it works best with large data sets.


## Run-times Mathematically
Sorting Algorithm   |   Best Run-time   |   Average Run-time   |   Worst Run-time
  Bubble Sort             Ω(n)                Θ(n^2)                 O(n^2)
  Selection Sort          Ω(n^2)              θ(n^2)                 o(n^2)
  Insertion Sort          Ω(n)                θ(n^2)                 o(n^2)
  Quick Sort              Ω(n log n)          θ(n log n)             o(n^2)
  Merge Sort              Ω(n log n)          θ(n log n)             o(n log n)

  - The fastest possible comparison sort available at a basic level has a run-time of n(n log n).