# ArrayList
## Implemented in C++

This projects is being used as a learning exercise for C++. The goal is to implement the ArrayList data structure as done in Java which can hold generic types. 

A few notes about this implementation:
1. The growth policy will be to double in size whenever an insertion overtakes the alloted array size.
2. When the size of the array is greater than what can be allocated in one contiguous block, version one will throw an error. Future versions will create a list of blocks containing the values and shuffle things aroudn through them accordingly.


