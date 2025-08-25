# Experiment No: 1a PythonWrite a python function "remove" that accepts a string and removes all the vowels from the string.


## AIM  
ToWrite a python function "remove" that accepts a string and removes all the vowels from the string.



## ALGORITHM  
Step 1: Start the program.
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions.
Step 4: Display the result/output to the user.
Step 5: Stop the program.

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
<img width="682" height="246" alt="image" src="https://github.com/user-attachments/assets/efeeec6c-f65f-437a-b0a3-0ff50f21b08f" />


## RESULT
Theprogram was successfully executed
# Experiment No: 1b For the given list, filter all elements that do not contain e.


## AIM  
To For the given list, filter all elements that do not contain e.



## ALGORITHM  
Step 1: Start the program.
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions.
Step 4: Display the result/output to the user.
Step 5: Stop the program.

## PROGRAM
```
import re
items = ['goal','new','user','sit','eat','dinner']
print([w for w in items if not re.search(r'e',w)])

```

## OUTPUT
<img width="544" height="230" alt="image" src="https://github.com/user-attachments/assets/84ebde18-4572-4c50-8e30-b38c47cef42a" />


## RESULT
Theprogram was successfully executed

# Experiment No: 1c Write a non fruitful and non parameterized function to get two lists and extend the second list with the first and print the resultant list.


## AIM  
To Write a non fruitful and non parameterized function to get two lists and extend the second list with the first and print the resultant list.


## ALGORITHM  
Step 1: Start the program.
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions.
Step 4: Display the result/output to the user.
Step 5: Stop the program.

## PROGRAM
```
def extendlist():
    a = eval(input())
    b = eval(input())
    res=b+a
    print("List1=",a)
    print("List2=",res)
    print(f"Resultant List={res}")


```

## OUTPUT
<img width="782" height="291" alt="image" src="https://github.com/user-attachments/assets/7282cf0d-5626-4b1b-8097-94dee60ba459" />


## RESULT
Theprogram was successfully executed

# Experiment No: 1d Write a python function that get two tuples, slice the second tuple elements between the indices 1 and 3. Also add that sliced tuple to the first tuple.

## AIM  
ToWrite a python function that get two tuples, slice the second tuple elements between the indices 1 and 3. Also add that sliced tuple to the first tuple.



## ALGORITHM  
Step 1: Start the program.
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions.
Step 4: Display the result/output to the user.
Step 5: Stop the program.

## PROGRAM
```
def tuples():
    tuple1 = eval(input())
    tuple2 = eval(input())

    # Extract first two elements from tuple2 and combine with all of tuple1
    result = tuple2[1:3] + tuple1

    print("tuple1=" + str(tuple1))
    print("tuple2=" + str(tuple2))
    print("Resultant tuple=" + str(result))


```

## OUTPUT
<img width="776" height="282" alt="image" src="https://github.com/user-attachments/assets/93d34010-6287-4863-a886-7e9db6290be8" />


## RESULT
Theprogram was successfully executed

# Experiment No: 1E  Write a python program to define a function that accepts 3  values and return its  multiplication.



## AIM  
ToWrite a python program to define a function that accepts 3  values and return its  multiplication.




## ALGORITHM  
Step 1: Start the program.
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions.
Step 4: Display the result/output to the user.
Step 5: Stop the program.

## PROGRAM
```
def mul(a,b,c):
    return d
    
    
    
a=int(input())
b=int(input())
c=int(input())
d=a*b*c
print("Multiply is",d)

```

## OUTPUT
<img width="650" height="293" alt="image" src="https://github.com/user-attachments/assets/9ab3188f-55ca-4682-a3bc-4049330de816" />


## RESULT

The program was successfully executed


xecuted

