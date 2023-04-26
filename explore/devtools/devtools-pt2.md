## Question 1
The bug was when num1 and num2 values were added, they were treated as strings, which resulted in string concatenation rather than numeric addition.

## Question 2
I would add a change num1 + num2 in line 11 to Number(num1) + Number(num2).