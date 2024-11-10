# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 16/08/2024                                                                        
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
![image](https://github.com/user-attachments/assets/0c54d3bf-2457-4320-be28-02fdfe5b3d32)


b)
![image](https://github.com/user-attachments/assets/5aad4051-6bf8-4696-b736-389a750a7a1a)

c)
![image](https://github.com/user-attachments/assets/0f071498-dd0e-43c0-a18f-75f0d1e61f0e)

d)
![image](https://github.com/user-attachments/assets/b467f91c-a685-4029-a647-782b7c80d6a5)

e)
![image](https://github.com/user-attachments/assets/87e0a714-f7e1-4380-a17b-929c4f7e3f02)



### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


