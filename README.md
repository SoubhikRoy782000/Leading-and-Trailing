# Leading-and-Trailing

Aim - 

To implement Leading and Trailing

Algorithm –

Step 1 – For Leading, check for the first non-terminal.
Step 2 – If found, print it.
Step 3 – Look for next production for the same non-terminal.
Step 4 – If not found, recursively call the procedure for the single non-terminal present before the comma or End Of Production String.
Step 5 – Include it’s results in the result of this non-terminal.
Step 6 – For trailing, we compute same as leading but we start from the end of the production to the beginning.
