# Stack-Parenthesis Balancing

## Task 1

Input Your program will take an arithmetic expression as a String input. For Example:

“1+2*(3/4)”

“1+2*[33+{4–5(6(7/8/9)+10)–11+(128)]+14”

“1+2*[33+{4–5(6(7/8/9)+10)}–11+(128)/{13+13}]+14”

Program

Your program will determine whether the open brackets (the square brackets, curly braces and the parentheses) are closed in the correct order.

Outputs:

Output 1

1+2*(3/4) This expression is correct.

Output 2

1+2*[33+{4–5(6(7/8/9)+10)–11+(128)]+14 This expression is NOT correct. Error at character # 10. ‘{‘- not closed.

Output 3

1+2*[33+{4–5(6(7/8/9)+10)}–11+(128)/{13+13}]+14 This expression is correct.

Output 4

1+2][33+{4–5(6(7/8/9)+10)–11+(12*8)]+14 This expression is NOT correct. Error at character # 4. ‘]‘- not opened. Task 1 Solve the above problem using an array based stack.

## Task 2

Solve the above problem using a linked list based stack.
