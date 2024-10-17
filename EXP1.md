# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                         
### REGISTER NUMBER : 212221040089

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

a)do while
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        while True:
            print(start, end=' ')
            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")

display()
```
b)while
```
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ")

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)
    
    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")
```
c)switch
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    n = input('Enter a value for N: ')
    
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()

```
d)if else
```
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)
        
        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")

compare()

```
e)for
```
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")

iterate()

```

### Output:

a)
![image](https://github.com/user-attachments/assets/e9cbea8b-8302-457b-aa8a-293dd52f59b4)
b)
![image](https://github.com/user-attachments/assets/260b2303-3c7f-473c-b4e2-eb05fb0830d9)
c)
![image](https://github.com/user-attachments/assets/7f17eaf7-154c-4265-b09f-10f6e6357a82)
d)
![image](https://github.com/user-attachments/assets/b2b5040f-2510-43eb-bbcc-0a0c49d6a032)
e)
![image](https://github.com/user-attachments/assets/7d650ebf-65a4-4bcd-a8e8-f7d466449b41)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


