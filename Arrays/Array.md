# <h1> Array </h1>

## <h2> Summary 
Array is a collection of items stored in contiguous memory location. Makes it easy to calculate the position of each element using offset to a base value

https://media.geeksforgeeks.org/wp-content/uploads/array-2.png

## <h2> Cheat sheet 
* Quick lookup / access ) O(1)
* Expensive to expand pre-allocated space O(n)
* Can't change the size
* Arrays have better cache locality ( access memory space repeatedly for short period of time ) - big for performance



## <h2> Java Array
* Arrays are dynamically allocated
  * need to declare reference variable then allocate space
* use length to get size of Array ( c/ c++ use sizeOf)
* Array variable can be decalred
* size of array must be int
* Arrays implement cloneable and java.io.serializable
* Array items can be primitive and non-primitive classes
* can use array literals { 1, 2, 3 }
* Deep clone vs shallow clone
  * Copy of addresses vs copy of values
* int intArray[]; intArray = new int[20]
* int[] intArray = new int[20]; 
