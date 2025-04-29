# Exp.No:3a
## STRING - FIND AND REPLACE


### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.


### ALGORITHM

1. Begin the program.  
2. Input the original string `str1` and the word to be replaced `replace_str`.  
3. Ask the user to input the new replacement word `str2`.  
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.  
5. Store the modified string in `str3`.  
6. Display the original string (`str1`) and the modified string (`str3`).  
7. Terminate the program.


### PROGRAM

```
def convert(string):
    result=""
    for char in string:
        if char.isalpha():
            result+="#"
        elif char.isdigit():
            result+="A"
        else:
            result+="5"
    print(result)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/78ff306d-3b37-4f03-a187-9a153476348f)


### RESULT
Thus the python program to accept a string, identify a word to be replaced, and replace it with a new word provided by the user is implemented and excecuted successfully.
