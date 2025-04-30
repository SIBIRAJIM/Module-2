# Exp.No:2d
## LOOPING PATTERNS - RIGHT HANDLED TRIANGLE PYRAMID PATTERN

---

### AIM  
To write a Python program to print the right handled triangle pyramid pattern of Stars. Get the no of rows as input.


### ALGORITHM

1. Start
2. Input an integer n (number of rows).
3. Loop i from 0 to n - 1: ← (each row)
   -Loop j from 0 to n - i - 2:
       -Print two spaces ' ' (for right alignment), without newline.
   -Loop j from 0 to i:
      -Print '* ' (asterisk followed by space), without newline.
   -Print a newline character to move to the next row.
4. End

### PROGRAM
```
#Reg.No:212223050048
#Name:SIBIRAJI M
#Add Your Code Here
n=int(input())
for i in range(n):
    for j in range(n-i-1):
        print(' ',end=' ')
    for j in range(i+1):
        print("*",end=" ")
    print()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/cac1f905-7729-4db1-99e1-d0d01e22f4d2)


### RESULT

Thus the Python program to print the right handled triangle pyramid pattern of Stars. Get the no of rows as input is executed successfully.

