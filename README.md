# Experiment 7: While Loop and Control Statements in Python

---

## Aim

To study and implement the **while loop**, along with **break** and **continue** statements in Python, and to develop programs for number operations such as factorial, Fibonacci series, palindrome checking, reversing numbers, counting digits, and searching elements in a list.

---

## Theory

A **while loop** in Python is used to repeatedly execute a block of statements as long as a given condition is true.

### Syntax

```python
while condition:
    statements
```

- The loop continues until the condition becomes **False**.
- It is known as an **entry-controlled loop** because the condition is checked before execution.

---

### Control Statements

#### 1. break statement
- Terminates the loop immediately even if the condition is true.

#### 2. continue statement
- Skips the current iteration and moves to the next iteration of the loop.

---

### Applications of While Loop

- Printing sequences  
- Calculating factorial  
- Generating Fibonacci series  
- Reversing numbers  
- Checking palindrome  
- Counting digits  
- Searching elements in lists  

---

# Algorithms

---

## 7.1 Print i as long as i is less than 6

### Algorithm

1. Start  
2. Initialize `i = 1`  
3. While `i <= 5`  
   - Print `i`  
   - Increment `i` by 1  
4. Stop  

---

## 7.2 Print Numbers from 1 to n

### Algorithm

1. Start  
2. Input number `n`  
3. Initialize `i = 1`  
4. While `i <= n`  
   - Print `i`  
   - Increment `i`  
5. Stop  

---

## 7.3 Factorial of a Number

### Algorithm

1. Start  
2. Input number `n`  
3. Set `fact = 1`  
4. While `n > 0`  
   - `fact = fact × n`  
   - Decrement `n`  
5. Print `fact`  
6. Stop  

---

## 7.4 Fibonacci Series (n terms)

### Algorithm

1. Start  
2. Input number of terms `n`  
3. Initialize `a = 0`, `b = 1`, `i = 1`  
4. While `i <= n`  
   - Print `a`  
   - `c = a + b`  
   - `a = b`  
   - `b = c`  
   - Increment `i`  
5. Stop  

---

## 7.5 Fibonacci Series (up to limit)

### Algorithm

1. Start  
2. Input `limit`  
3. Initialize `a = 0`, `b = 1`  
4. While `a <= limit`  
   - Print `a`  
   - Update `a, b = b, a + b`  
5. Stop  

---

## 7.6 Reverse a Number

### Algorithm

1. Start  
2. Input number `num`  
3. Set `rev = 0`  
4. While `num > 0`  
   - `digit = num % 10`  
   - `rev = rev × 10 + digit`  
   - `num = num // 10`  
5. Print `rev`  
6. Stop  

---

## 7.7 Check Palindrome Number

### Algorithm

1. Start  
2. Input number `num`  
3. Store original number in `temp`  
4. Set `rev = 0`  
5. While `num > 0`  
   - `rev = rev × 10 + num % 10`  
   - `num = num // 10`  
6. If `temp == rev`  
   - Print "Palindrome"  
   Else  
   - Print "Not Palindrome"  
7. Stop  

---

## 7.8 Check Palindrome String (using while loop)

### Algorithm

1. Start  
2. Input string `s`  
3. Set `i = 0`, `j = length(s) - 1`  
4. Set `is_palindrome = True`  
5. While `i < j`  
   - If `s[i] != s[j]`  
     - Set `is_palindrome = False`  
     - Break loop  
   - Increment `i`  
   - Decrement `j`  
6. If `is_palindrome` is True  
   - Print "Palindrome"  
   Else  
   - Print "Not Palindrome"  
7. Stop  

---

## 7.9 Check Palindrome using if statement (Slicing)

### Algorithm

1. Start  
2. Input string `st`  
3. Reverse string using slicing (`st[::-1]`)  
4. If original string equals reversed string  
   - Print "Palindrome"  
   Else  
   - Print "Not Palindrome"  
5. Stop  

---

## 7.10 Count Digits in a Number

### Algorithm

1. Start  
2. Input number `num`  
3. Set `count = 0`  
4. While `num > 0`  
   - Increment `count`  
   - `num = num // 10`  
5. Print `count`  
6. Stop  

---

## 7.11 Exit Loop using Break

### Algorithm

1. Start  
2. Initialize `i = 1`  
3. While `i < 6`  
   - Print `i`  
   - If `i == 3`  
     - Break  
   - Increment `i`  
4. Stop  

---

## 7.12 Search an Element in a List

### Algorithm

1. Start  
2. Initialize list `nums`  
3. Input element `key`  
4. Set `i = 0`  
5. While `i < length(nums)`  
   - If `nums[i] == key`  
     - Print index  
     - Break  
   - Increment `i`  
6. If loop completes without break  
   - Print "Element not Found"  
7. Stop  

---

## 7.13 Print Only Odd Numbers (1 to 10)

### Algorithm

1. Start  
2. Initialize `i = 0`  
3. While `i < 10`  
   - Increment `i`  
   - If `i % 2 == 0`  
     - Continue  
   - Print `i`  
4. Stop  

---

## Conclusion

In this experiment, we successfully implemented the **while loop** in Python to solve various problems such as factorial calculation, Fibonacci series generation, palindrome checking, reversing numbers, counting digits, and searching elements in a list.

We also learned:

- How entry-controlled loops work  
- The use of **break** to terminate a loop  
- The use of **continue** to skip iterations  
- Practical applications of loops in solving mathematical and logical problems  

Thus, the experiment helped in understanding looping concepts and control flow statements effectively.

