# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
~~~
 import random

minimum = int(input("Enter minimum value: "))
maximum = int(input("Enter maximum value: "))

numbers = list(range(minimum, maximum + 1))

random.shuffle(numbers)

print("Random numbers between", minimum, "and", maximum, "are:")

for num in numbers:
    print(num, end=" ")
~~~


# OUTPUT:
<img width="932" height="372" alt="image" src="https://github.com/user-attachments/assets/1621e222-5e67-4a3e-9199-71a7fe95957d" />

# RESULT:
Thus, the Python program for implementing Pseudorandom Number Generation using the standard library was executed successfully.
