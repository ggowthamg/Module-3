# Exp.No:3c
## LIST - ODD NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all odd numbers up to **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is odd, append `i` to the list `l`.  
5. Print the final list `l` containing all the odd numbers.  
6. Terminate the program.

---

### PROGRAM

```
def createlist(n):
    l = []
    for i in range(0,n):
        if i % 2 != 0:
            l.append(i)
    print("List =",l)
    print("Sum of the list =",sum(l))
```

### OUTPUT
![image](https://github.com/user-attachments/assets/2f208e87-47ba-40ab-b1a3-bd0aac88d2e5)

### RESULT
Thus the program ODD NUMBERS LIST have been executed and verified sucessfully
