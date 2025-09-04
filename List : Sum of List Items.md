## AIM
To Write a python function "remove" that accepts a string and removes all the vowels from the string.

## ALGORITHM
```
Step 1: Start the program. Step 2: Take the necessary input(s) from the user. Step 3: Process the input(s) using suitable operations or conditions. Step 4: Display the result/output to the user. Step 5: Stop the program.
```

## PROGRAM
```
def remove(s):
    vowels = "aeiouAEIOU"
    result = ""
    for char in s:
        if char not in vowels:
            result += char
    return result
```


## OUTPUT
<img width="843" height="300" alt="image" src="https://github.com/user-attachments/assets/883958f3-8154-45e0-9807-23e77614e8ab" />

## RESULT
Theprogram was successfully executed
