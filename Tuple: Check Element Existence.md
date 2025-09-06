## AIM
To Write a python function that get two tuples, slice the second tuple elements between the indices 1 and 3. Also add that sliced tuple to the first tuple.

## ALGORITHM
Step 1: Start the program. Step 2: Take the necessary input(s) from the user. Step 3: Process the input(s) using suitable operations or conditions. Step 4: Display the result/output to the user. Step 5: Stop the program.

## PROGRAM
def tuples():
    tuple1 = eval(input())
    tuple2 = eval(input())

    # Extract first two elements from tuple2 and combine with all of tuple1
    result = tuple2[1:3] + tuple1

    print("tuple1=" + str(tuple1))
    print("tuple2=" + str(tuple2))
    print("Resultant tuple=" + str(result))


## OUTPUT
<img width="922" height="337" alt="image" src="https://github.com/user-attachments/assets/abfa4bcf-5f48-4e81-9eef-89f5357f93de" />

## RESULT
Theprogram was successfully executed 
