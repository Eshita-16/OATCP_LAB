largestNumber(nums):
    1. Convert each integer in nums to its string representation and store them in a list of strings nums_str.
    2. Define a custom comparison function compare(a, b) that compares strings a and b based on their concatenations a + b and b + a.
    3. Sort the list of strings nums_str in non-ascending order using the custom comparison function compare.
    4. Concatenate the sorted strings in nums_str to form the largest number and store it in result.
    5. Remove leading zeros from result.
    6. Return result.

