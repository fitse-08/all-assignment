

## Algorithm to Find the Smallest Number in an Array
Start.
Input: Define an array of integers numbers[] and determine its size.
Check Array Size: -If the size of the array is less than or equal to 0: -Throw an invalid_argument exception with the message "The array is empty."
Initialize: Set the variable smallest to the first element of the array (numbers[0]).
Iterate through the Array: -For each element in the array from index 1 to size - 1: -If the current element (numbers[i]) is less than smallest: -Update smallest to numbers[i].
Output: Return the value of smallest.
Exception Handling: -In the main function, wrap the function call in a try-catch block. -If an exception is thrown, catch it and print the error message.
End.
## Algorithm to Find Second Largest Number
Input: An array of integers and its size.
Output: The second largest number in the array, or an error message if not applicable.
Steps:
Check Size: -If size < 2, print "Error: Not enough elements." and return -1.
Initialize Variables: -Set largest to the smallest possible integer (e.g., -2147483648). -Set secondLargest to the smallest possible integer (e.g., -2147483648).
Iterate Through the Array: -For each element numbers[i] in the array: -If numbers[i] is greater than largest: -Set secondLargest to largest. -Update largest to numbers[i]. -Else If numbers[i] is greater than secondLargest and not equal to largest: -Update secondLargest to numbers[i].
Check for Second Largest: -If secondLargest is still -2147483648, print "Error: No second largest number." and return -1.
Return Result: -Return secondLargest.
## Algorithm to Find Third Largest Number
Input: An array of integers and its size.
Output: The third largest number in the array, or an error message if not applicable.
Steps:
Check Size: -If size < 3, print "Error: Not enough elements." and return -1.
Initialize Variables: -Set largest to the smallest possible integer (e.g., -2147483648). -Set secondLargest to the smallest possible integer (e.g., -2147483648). -Set thirdLargest to the smallest possible integer (e.g., -2147483648).
Iterate Through the Array: -For each element numbers[i] in the array: -If numbers[i] is greater than largest: -Update thirdLargest to secondLargest. -Update secondLargest to largest. -Update largest to numbers[i]. -Else If numbers[i] is greater than secondLargest and not equal to largest: -Update thirdLargest to secondLargest. -Update secondLargest to numbers[i]. -Else If numbers[i] is greater than thirdLargest, not equal to secondLargest, and not equal to largest: -Update thirdLargest to numbers[i].
Check for Third Largest: -If thirdLargest is still -2147483648, print "Error: No third largest number." and return -1.
Return Result: -Return thirdLargest.