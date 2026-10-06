# python2


# Practical no 1

# Different data types

name = "Anita"          # String
rint("Name:", name, "Type:", type(name))
print("Age:", age, "Type:", type(age))
print("Height:", height, "Type:", type(height))
print("Student:", is_student, "Type:", type(is_student))

result = 0        # to store sum of cubes of digits

while num > 0:
    digit = num % 10        # get the last digit
    result = result + digit ** 3   # add cube of digit to result
    num = num // 10          # remove the last digit

if result == original:
    print(original, "is an Armstrong number")
else:
    print(original, "is not an Armstrong number")

# Aim: B) Write a Python program to demonstrate the use of break and continue statements in loops.
codes:- 

# Demonstration of break

print("Using break:")for i in range(1, 6):
    if i == 4:
        break
    print(i)

# Demonstration of continue
print("\nUsing continue:")
for i in range(1, 6):
    if i == 3:
        continue
    print(i)









# Practical No.03

Aim: a. Write a Python program to check whether a number is even or odd.
Code:
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even Number")
else:
    print("Odd Number")


# Aim: b. Write a Python program to find the largest among three numbers.

Code:
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    print("Largest number is:", a)
elif b >= a and b >= c:
    print("Largest number is:", b)
else:
    print("Largest number is:", c)









# Practical No.04

Aim: a. Write a Python program to convert Celsius to Fahrenheit.

Code:
celsius = float(input("Enter temperature in Celsius: "))
fahrenheit = (celsius * 9/5) + 32
print("Temperature in Fahrenheit:", fahrenheit)



Aim: b. Write a Python program to make a simple calculator (addition, subtraction, multiplication, division).
Code:
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

print("Addition =", a + b)
print("Subtraction =", a - b)
print("Multiplication =", a * b)
print("Division =", a / b)




# Practical No.5

Aim: a. Write a Python program to find HCF (GCD) of two numbers.

Code:
# Program to find HCF (GCD) of two numbers
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
while num2 != 0:
    temp = num2
    num2 = num1 % num2
    num1 = temp
print("HCF (GCD) =", num1)


 Aim: b. Write a Python program to convert a decimal number to binary, octal, and hexadecimal. 

Code:
# Program to convert decimal number
num = int(input("Enter a decimal number: "))
print("Binary =", bin(num))
print("Octal =", oct(num))
print("Hexadecimal =", hex(num))





# Practical No.06

Aim: a. Write a Python program to add two numbers.

Code:
# Program to add two numbers
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
sum = num1 + num2
print("Sum =", sum)

Output:


Aim: b. Write a Python program to calculate the area of a triangle.

Code:
# Program to calculate the area of a triangle
base = float(input("Enter base: "))
height = float(input("Enter height: "))
area = 0.5 * base * height
print("Area of triangle =", area)



# Practical No.7

Aim: a. Python Program to Apply Indexing and Slicing on an Array

Code:
# Create an array
numbers = [10, 20, 30, 40, 50]

# Indexing
print("First element:", numbers[0])
print("Third element:", numbers[2])

# Slicing
print("First three elements:", numbers[0:3])
print("Last three elements:", numbers[2:5])

Output:



Aim:b. Python Program to Add and Remove Elements from an Array.

Code:
# Create an array
numbers = [10, 20, 30]

print("Original array:", numbers)

# Add an element
numbers.append(40)
print("After adding 40:", numbers)

# Add an element at a specific position
numbers.insert(1, 15)
print("After inserting 15:", numbers)

# Remove an element
numbers.remove(30)
print("After removing 30:", numbers)

# Remove the last element
numbers.pop()
print("After removing last element:", numbers)







# Practical No.8

Aim: a. Python Program to Demonstrate String Immutability and Multiline String.

Code:
# String immutability

name = "Hello"
print("Original string:", name)

# Trying to change a character
# name[0] = "Y"   # This will give an error

# Creating a new string
name = "Yellow"
print("New string:", name)

# Multiline string
message = """Python is easy to learn.
Python is widely used.
Python is a popular programming language."""

print("\nMultiline string:")
print(message)


Aim: b. Python Program to Compare and Concatenate Two Strings.

Code:
# Two strings
str1 = "Python"
str2 = "Python"

# Comparing strings
if str1 == str2:
    print("Both strings are equal")
else:
    print("Both strings are different")

# Concatenating strings
first = "Hello"
second = "Python"

result = first + " " + second

print("Concatenated string:", result)






# Practical No.9

Aim: a. Python Program to Remove Punctuation from a String
Code:
import string
text = "Hello, World! Python is easy."
result = ""
for char in text:
    if char not in string.punctuation:
        result = result + char
print("Original string:", text)
print("String without punctuation:", result)



b. Python Program to Check Whether a String is Palindrome or Not 
ft
A
Code:
text = input("Enter a string: ")
reverse = text[::-1]
if text == reverse:
    int("The string is a palindrome")
else:
    print("The string is not a palindrome")





# Practical No.10

Aim:a. Python Program to Swap Two Variable. 

The vNo


# Input two numbers
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print("Before swapping:")
print("a =", a)
print("b =", b)



Aim: b. Python Program to Shuffle a Deck of Cards
Theory:The fi

Code:
import random
deck of cards
suits = ["Hearts", "Diamonds", "Clubs", "Spades"]
"10", "Jack", "Queen", "King", "Ace"]

Create cards
for rank in ranks:
        deck.append(rank + " of " + suit)
Shuffle the deck
random.shuffle(deck)

# Display shuffled cards
print("Shuffled deck:")

for card in deck:
    print(card)



Aim: c. Python Program to Import Built-in and User-defined Modules


le")

t(name):
    return "Hello, " + name

mymodule.greet = greet

# Built-in module
print("Square root of 25:", math.sqrt(25))

# User-defined module
print(mymodule.greet("Anita"))

# Swap the variables
a, b = b, a
rint("a =", a)
print("b =", b)
