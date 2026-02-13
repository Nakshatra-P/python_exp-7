Aim

To study and implement the while loop, along with break and continue statements in Python, and to develop programs for number operations such as factorial, Fibonacci series, palindrome checking, reversing numbers, counting digits, and searching elements in a list.

Theory

A while loop in Python is used to repeatedly execute a block of statements as long as a given condition is true.

Syntax:
while condition:
    statements


The loop continues until the condition becomes False.

It is also known as an entry-controlled loop because the condition is checked before execution.

Control Statements Used

break statement

Terminates the loop immediately even if the condition is true.

continue statement

Skips the current iteration and moves to the next iteration of the loop.

Applications of While Loop

Printing sequences

Calculating factorial

Generating Fibonacci series

Reversing numbers

Checking palindrome

Counting digits

Searching elements in lists

Algorithms
7.1 Print i as long as i is less than 6
Algorithm

Start

Initialize i = 1

While i <= 5

Print i

Increment i by 1

Stop

7.2 Print Numbers from 1 to n
Algorithm

Start

Input number n

Initialize i = 1

While i <= n

Print i

Increment i

Stop

7.3 Factorial of a Number
Algorithm

Start

Input number n

Set fact = 1

While n > 0

fact = fact × n

Decrement n

Print fact

Stop

7.4 Fibonacci Series (n terms)
Algorithm

Start

Input number of terms n

Initialize a = 0, b = 1, i = 1

While i <= n

Print a

c = a + b

a = b

b = c

Increment i

Stop

7.5 Fibonacci Series (up to limit)
Algorithm

Start

Input limit

Initialize a = 0, b = 1

While a <= limit

Print a

Update a, b = b, a + b

Stop

7.6 Reverse a Number
Algorithm

Start

Input number num

Set rev = 0

While num > 0

digit = num % 10

rev = rev × 10 + digit

num = num // 10

Print rev

Stop

7.7 Check Palindrome Number
Algorithm

Start

Input number num

Store original number in temp

Set rev = 0

While num > 0

rev = rev × 10 + num % 10

num = num // 10

If temp == rev

Print "Palindrome"
Else

Print "Not Palindrome"

Stop

7.8 Check Palindrome String (using while loop)
Algorithm

Start

Input string s

Set i = 0, j = length(s) - 1

Set is_palindrome = True

While i < j

If s[i] != s[j]

Set is_palindrome = False

Break loop

Increment i

Decrement j

If is_palindrome is True

Print "Palindrome"
Else

Print "Not Palindrome"

Stop

7.9 Check Palindrome using if statement
Algorithm

Start

Input string st

Reverse string using slicing

If original string equals reversed string

Print "Palindrome"
Else

Print "Not Palindrome"

Stop

7.10 Count Digits in a Number
Algorithm

Start

Input number num

Set count = 0

While num > 0

Increment count

num = num // 10

Print count

Stop

7.11 Exit Loop using Break
Algorithm

Start

Initialize i = 1

While i < 6

Print i

If i == 3

Break

Increment i

Stop

7.12 Search an Element in a List
Algorithm

Start

Initialize list nums

Input element key

Set i = 0

While i < length(nums)

If nums[i] == key

Print index

Break

Increment i

If loop completes without break

Print "Element not Found"

Stop

7.13 Print Only Odd Numbers (1 to 10)
Algorithm

Start

Initialize i = 0

While i < 10

Increment i

If i % 2 == 0

Continue

Print i

Stop

Conclusion

In this experiment, we successfully implemented the while loop in Python to solve various problems such as factorial calculation, Fibonacci series generation, palindrome checking, reversing numbers, counting digits, and searching elements in a list.

We also learned:

How entry-controlled loops work.

The use of break to terminate a loop.

The use of continue to skip iterations.

Practical applications of loops in solving mathematical and logical problems.

Thus, the experiment helped in understanding looping concepts and control flow statements effectively.
