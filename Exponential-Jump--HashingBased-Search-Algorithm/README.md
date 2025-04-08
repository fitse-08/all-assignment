# Exponential-Jump--HashingBased-Search-Algorithm

## Exponential Search
### Description
   * Exponential Search is used to find the position of an element in a sorted array. It works by:
        1. Finding a range where the element could be present by doubling the step size (1, 2, 4, 8, etc.).
        2. Once the range is determined, it uses binary search within that range.
### Time Complexity  
    * Best case: O(1)
    * Average/Worst case: O(log n)

## Jump Search
### Description
   * Jump Search is another searching algorithm for sorted arrays. It works by jumping ahead by a fixed step size (sqrt(n)) to find the range where the target could be, and then performing a linear search within that range.
### Time Complexity
   * Best case: O(1)
   * Average/Worst case: O(√n)

## Hashing-based Search
### Description
   * Hashing-based searching involves using a hash table to store elements for fast lookup. A hash function maps keys to indices in the table. Searching is typically O(1) for well-designed hash functions.
### Time Complexity
   * Best case: O(1) (direct lookup)
   * Worst case: O(n) (if hash collisions occur)

### Comparison of Exponential, Jump, and Hashing-based Search
### Algorithm	    Best      Worst       Space             Use Case
                  Case 	    Case	    Complexity	

Exponential 	    O(1)	 O(log n)	   O(1)	             * Sorted arrays, 
Search                                               large data with unknown 
                                                     size.

Jump        	    O(1)	   O(√n)	   O(1)	             * Sorted arrays, when binary search     
Search                                                 can't be used.

Hashing	            O(1)	   O(n)	       O(n)	        * Large datasets with
                                                     fast lookup requiring
                                                     constant-time access.
## Student Informaint
  * Name: Natnael Tsedeke
  * ID: RMNS-7783/23
  * Course: DSA
                                                     