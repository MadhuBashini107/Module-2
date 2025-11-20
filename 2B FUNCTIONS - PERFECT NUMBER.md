# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Start the program.

2. Read input from the user and store it in variable `n`.

3. Convert the input value to an integer.

4. Define a function `is_perfect(num)` with the following steps:
   - Initialize `sum_of_divisors` to `0`.
   - Loop through all numbers from `1` to `num - 1`.
   - For each number `i`, check:
     - If `num % i == 0`, then `i` is a divisor.  
       - Add `i` to `sum_of_divisors`.
   - After finishing the loop, return `True` if `sum_of_divisors` is equal to `num`, otherwise return `False`.

5. In the main program:
   - Call the function `is_perfect(n)`.
   - If the returned value is `True`, print "The number is a Perfect number!".
   - Otherwise, print "The number is not a Perfect number!".

6. End the program.


---

### PROGRAM
```python
def is_perfect(num):
    sum_of_divisors = 0
    for i in range(1, num):
        if num % i == 0:
            sum_of_divisors += i
    return sum_of_divisors == num

n = int(input())

if is_perfect(n):
    print("The number is a Perfect number!")
else:
    print("The number is not a Perfect number!")

```
### OUTPUT

<img width="935" height="258" alt="image" src="https://github.com/user-attachments/assets/9c043a4d-6b5b-4e7b-8a47-5c4d743f210e" />

### RESULT
Hence, a Python program is executed to verify if a number is a perfect number using the concepts of functions.
