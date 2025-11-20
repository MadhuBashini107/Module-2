# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - To calculate the value of the following expression by using a lambda function.
---

### AIM  
To write a Python program to calculate the value of the following expression $(x / 10) \cdot (y / 2) \cdot z$ by using a lambda function.

---

### ALGORITHM

1. Begin Program
Start the execution of the Python script.
2. Define Function `exp`
Define a lambda function named exp that takes three arguments: x, y, and z.
3. Acquire Input for `x`
Prompt the user for input. Convert the input string to an integer and store the result in the variable x.
4. Acquire Input for `y`
Prompt the user for input. Convert the input string to an integer and store the result in the variable y.
5. Acquire Input for `z`
Prompt the user for input. Convert the input string to an integer and store the result in the variable z.
6. Calculate and Output Result
Call the lambda function exp with x, y, and z.  
The function performs the calculation (x/10) × (y/2) × z, and the final result is printed to the console.
7. Terminate Program
End the execution of the script.

---


### PROGRAM

```python
exp= lambda x,y,z: (x/10)*(y/2)*z
x=int(input())
y=int(input())
z=int(input())
print(exp(x,y,z))
```

### OUTPUT

<img width="933" height="308" alt="Screenshot 2025-11-20 143221" src="https://github.com/user-attachments/assets/650e327d-f39b-4303-86d1-2410873e1750" />



### RESULT

Hence, a python program is executed to calculate the valueof the following expression $(x / 10) \cdot (y / 2) \cdot z$ by using a lambda function.

```
