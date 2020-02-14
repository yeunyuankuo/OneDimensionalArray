# OneDimensionalArray

##Properties of Array
* Array can store data of specified data type
* It has **contiguous** memory location
* Every "cell" of an array has unique index
* Index starts with 0 instead of 1
* Size of array needs to be specified mendatorily and cannot be modified.

##Definition of Array
Array is a datastructure consisting of a collection of elements, each identified by array index. An array is stored such that the position of each element can be computed from its index cell by a mathematical formula.

* One dimensional array: arr[col]
* Two dimensional array: arr[row][col]
* Three dimensional array: arr[depth][row][col]
*Java supports upto 255 dimensional array:clap::clap::clap:*

##Time and Space Complexity of 1D Array
Particulars | Time Complexity | Space Complexity
----------- | --------------- | ----------------
Creating an empty array | O(1) | O(N)
Inserting a value in an array | O(1) | O(1)
Traversing a given array | O(N) | O(1)
Accessing given cell # | O(1) | O(1)
Searching a given value | O(N) | O(1)
Deleting a cell's value | O(1) | O(1)
