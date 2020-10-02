
# Dynamic Arrays
 - The ever adjusting array of various sizes, doubles in size when filled.
 - The amount of distance between the numbers, as in their stored locations
   can become variable and cause writing and reading to slowdown slightly.
   There will be a slight performance loss. (A potentially nasty curve, dep. on size)
   ## o(n)

## Time complexity of tasks within a growing array
 - Finding the location to insert a new value will be, o(n) - linear time
 - Inserting a new value will still be, o(1) - constant time
 - If we double the size of the array every time it fills up, 
   while keeping track of our new write location,
   then our time becomes on average o(1) - constant time.


## How to add and compute insertion times
 - Ex: 
    o(1) + o(1) + o(n)
    2/3(o(1)) + 1/3(o(n))
    - The quicker value is removed, as the operation is
      as slow as the slowest part.
    Therefore, the time complexity is o(n)


# Circular Array
 - Loops over itself, when it hits its max,
   it automatically begins again at zero and
   persists as if in a circular loop. (Read/Write)
