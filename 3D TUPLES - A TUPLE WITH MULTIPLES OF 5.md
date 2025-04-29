# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.


### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

### PROGRAM

```
n=int(input())
a=[]
for i in range(5,n):
    if i%5==0:
        a.append(i)
b=tuple(a)
print(b)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/d228516f-e40c-46de-b6db-2a98adc00af7)


### RESULT
Thus the Python program to create a tuple containing all multiples of 5 up to a given number **N** is implemented and excecuted successfully.
