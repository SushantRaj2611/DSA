# LeetCode 1190 - Reverse Substrings Between Each Pair of Parentheses

## Approach

Use a stack.

1. Push characters into the stack.
2. When ')' is found, pop characters until '('.
3. Store popped characters in reverse order.
4. Remove '('.
5. Push the reversed characters back into the stack.
6. Finally construct the answer.

## Complexity

Time: O(n)

Space: O(n)