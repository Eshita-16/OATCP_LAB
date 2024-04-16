Algorithm:

1. totalHammingDistance Function:
   - For each bit position from 0 to 31:
     - Count the number of ones and zeros across all numbers in the vector.
     - Add the product of the counts to the total Hamming distance.

2. Main Function:
   - Open input and output files.
   - Read integers from the input file into a vector.
   - Call `totalHammingDistance` function.
   - Write the result to the output file.
   - Close both input and output files.

## Time Complexity: \( O(n) \), Space Complexity: \( O(1) \)
