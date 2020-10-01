
# How is data stored, aka. how is data stored on computers.

## Memory and Addresses
 - Locations that are used to store data are organized by addresses, 
   which can be accessed via address location to retrieve the data 
   stored at that address. Most commonly this is in hex decimal.

- When data is being used by a program but not essential to its immediate
  operation it will be stored in the RAM. If it is essential to the programs
  immediate function it will be stored in the cache of the CPU.

## Arrays and Index's / Accessors (Fixed Array)
 - An array is individual bits of data stored in sequence and organized in
   a logical order, with each position being associated with a location value.

- The beginning, or starting posiiton of an array is 0(zero indexing). As the array grows the order
  or size of positions grow by one with each new value, therefore increasing the size
  of the array.

- To access data in an array object, you type the name of the array with two brackets, 
  and in the brackets place the location value for the desired piece of data. 
  Such as: Array[2];

- The end of the array can always be counted with n-1.
  Lower level languages will allow you to go outside of these bounds and return 
  whatever is there.

- Fixed arrays don't grow, dynamic can be increasing with an increase to the defined size.

### Note:  An array can hold different types of data, though it's more common
###        to designate an array for a specific type of data.

 

