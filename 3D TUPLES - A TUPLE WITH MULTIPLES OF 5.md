# Exp.No:3d  
## DIVISIBLE BY 9 FROM 1

---

### AIM  
To write a Python program that generates a tuple containing all numbers divisible by 9 from 1 to a given number (exclusive), and displays the tuple along with its length.


---

### ALGORITHM

Start the program.
Input a number a from the user using int(input()).
Initialize an empty list l to store numbers divisible by 9.
Initialize a counter c to 0 for counting the number of divisible elements.
Use a for loop to iterate from 1 to a-1 (i.e., range(1, a)).
In each iteration, check if the number is divisible by 9 using if i % 9 == 0.
If divisible, append the number to the list l and increment the counter c by 1.
After the loop, convert the list l to a tuple using tuple(l) and print it.
Print the length of the tuple using the counter c.
End the program.

---

### PROGRAM

```
a = int(input())
l=[]
c=0
for i in range(1,a):
    if i%9==0:
        l.append(i)
        c+=1
print(tuple(l))
print(f'Length of the tuple is {c}')
```

### OUTPUT
![image](https://github.com/user-attachments/assets/c57f8335-3049-43f3-9e90-49be526ced5f)

### RESULT
Thus the program DIVISIBLE BY 9 FROM 1 have been executed and verified sucessfully
