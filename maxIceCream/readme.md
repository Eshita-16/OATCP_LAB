1. Start with the input array of ice cream bar prices (costs) and the number of coins available (coins).
2. Sort the ice cream bar prices in non-decreasing order.
3. Initialize a variable count to 0 to keep track of the number of ice cream bars bought.
4. Iterate over each ice cream bar price in the sorted array:
    a. If the number of coins is greater than or equal to the current ice cream bar price:
        - Subtract the ice cream bar price from the coins.
        - Increment the count of bought ice cream bars.
    b. If the number of coins is less than the current ice cream bar price, break the loop.
5. Return the count of bought ice cream bars.
