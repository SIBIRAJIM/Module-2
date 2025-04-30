# Exp.No:2b  
## FUNCTIONS - STRONG NUMBER

### AIM  
To write a Python program to check if a number is a Strong number using the concept of functions.

---

### ALGORITHM

1. Start
2. Define a function is_strong(num):
    - Initialize sum = 0
    -Store original number in temp = num
    -Repeat while num > 0:
        -Extract the last digit: digit = num % 10
        -Compute factorial of digit
        -Add factorial to sum
        -Remove last digit: num = num // 10
    -If sum == temp, return True
    -Else, return False
3. Input a number from the user and store it in n
4. Call the function is_strong(n)
5. If it returns True, print "Strong number"
6. Else, print "Not a strong number"
7. End


### PROGRAM
```
#Reg.No:212223050048
#Name:SIBIRAJI M
#Add your Code Here
import math
def strong(num):
    sum1=0
    temp=num
    while(num != 0):
        sum1 += math.factorial(num%10)
        num = num // 10
    if(sum1==temp):
        print("The number is a strong number")
    else:
        print("The number is not a strong number")


n=int(input())
strong(n)
```
### OUTPUT

![image](https://github.com/user-attachments/assets/c80842d6-f072-4609-add8-2384c7dc0e61)


### RESULT

Thus the Python program to check if a number is a Strong number using the concept of functions is executed successfully.
