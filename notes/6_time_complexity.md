
# Time Complexity

## Log
- A log(n) function is the inverse of an exponential function
    - It levels off instead of grows, it shows an initial growth followed by a leveling off.
## Factorials
- ex: 3!
    - means 1*2*3, which equals 6.
    - the multiplication of every number preceeding it.

## n notation
- n notation is the input to output scaling for 
    functions/methods/aglorithms or operations.

## n notation and scaling
- It's used to look for large patterns.
- Used to determine the run-time and efficiency.

### n-notation example
- Every cycle of a program takes .001 seconds.
    # How much faster will nlog(n) take than n^2 if 1,000 pieces of data are inputed.
    - n(log n) = 1000log(1000) = 9960 x.001 = 9.96 seconds
    - n^2 = 1000^2 = 1,000,000 *.001 = 1,000 seconds = 16.7 minutes run-time

    # How much faster will nlog(n) take than n^2 if 25,000 pieces of data are inputed.
    - n(log n) = 25000log(25000) = 365,000 * .001 = 6 minutes 5 seconds
    - n^2 = 25000^2 = 625,000,000 * .001 = ~ 7 days 5 hours

    # if n = 1000
    - 0(n), 1000
    - O(n^2), 1,000,000
    - O(log n)

# Big O Represents a Boundary
    - o(n), Faster                  | o(n^2), Faster than n^2
    - O(n), Faster or Equal         | O(nlogn), At worst will be nlogn
    - θ(n), Equal to                | θ(n), Equal to n
    - Ω(n), Slower or Equal to      | Ω(n^2), Slower or equal to n^2
    - ω(n), Slower Than             | ω(n), Slower than n^3
