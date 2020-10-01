
# Big O real-world examples



## Example 1, non-language specific
for each data in data list
{
    Print data to screen
}

 - eact represents individual pieces of data in the data list,
   which is then fed into our for loop.
 - Per each iteration had the next value in the list being assinged
   to data and passed into the loop for us to work with.

 - this has a run-time of O(n), or theta of n.


## Example 2, non-language specific
for each data "N" in data list
{
    // check if the Data is in list
    For each data "W" in data list
    {
        if N == W print True
    }
}

 - A new value, in order, is assigned to data"N" per each iteration,
   and passed into the function on the external For loop where on pass is made

 - Meanwhile on the internal loop, we have another for loop that iterates through 
   the same list and assigns a new value per iteration to data"W".

 - On the inside of both loops we have a simple logic statement comparing
   Data"N" and Data"W", if they are equal to one another we will see
   output to the screen of True. This will continue until both for-loops run
   out of items in their list.

 - The time complexity for this can be O(1) or O(n) depending on the amount of times
   needing to be run. If you look for the first instance, then it's O(1). Else,
   if you are seeking all occurances, then it will be O(n). Because the For-Loops are
   nested, we now see the time complexity of O(n^2). Which depending on if anything else is 
   nested - could become very time costly. This is not ideal.

