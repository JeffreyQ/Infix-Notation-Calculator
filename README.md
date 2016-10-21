# Infix-Notation-Calculator

Homework #1 for CIS 22C at De Anza College

Implementing the Stack and Queue abstract data types to evaluate simple mathematical expressions in infix notation.

The following lists our assumptions on the mathematical expressions entered by the user:

1. The mathematical expression in infix notation is a valid one (e.g. 1 + 2∗3 is valid while 1 +∗2 is not; or 5 is valid while +3∗4 / is not).
2. The operands of the given mathematical expression are integers from 0 to 9 only.
3. The only allowable operators are + (for addition), − (for subtraction), ∗ (for multiplication), / (for division), and ˆ (for exponentiation). Negative sign is not allowed.
4. Division by zero is not allowed.
5. The exponentiation operator has the highest precedence followed by the multiplication and division operators and finally the addition and subtraction operators.
6. The exponentiation operator is right-associative while all the other operators are left-associative. Parentheses can also appear in the mathematical expression.
8. Parentheses can be nested.
9. Assume that the parentheses are well-balanced.
10. Blank spaces can appear in the mathematical expression.
11. There is no limit as to the length of the mathematical expression. 12. The input is terminated when the user hits the ENTER key.
