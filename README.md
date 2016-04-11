# assign1
'''Instructions:

You should submit ONLY one doc (or docx or pdf) file named assign1.doc (or .docx or .pdf). Any other file format (like .py, .zip, .rar, etc.) is not allowed. This file should contain your python code for the program(s) and the screen shot(s) of your program's sample runs (with output). Make sure to put your python code correctly in this file (with correct indentation). If you have any text for the grader to read before grading, you can include it at the top of this file. 
You must use Python 3.x to implement these programs.
Your grade will be based on functionality (does the program do what it is suppose to do) and understandability (are the literals meaningful and is the code modular and well documented with appropriate comments).
In this assignment you will create two custom calculator programs. These programs follow a very common pattern in computing:

Take in data
Perform calculations
Output data
Programs take in data from sources like databases, 3D models, game controllers, keyboards, and the internet. They perform calculations and output the result. Sometimes we even do this in a loop thousands of times a second.

It is a good idea to do the calculations separate from the output of the data. While it is possible to do the calculation inside the print statement, it is better to do the calculation, store it in a variable, and then output it later. This way calculations and output aren't mixed together.

When writing programs it is a good idea to use blank lines to separate logical groupings of code (e.g., blocks, modules). For example, place a blank line between the input statements, the calculation, and the output statement.

____________________________________________________________________________________________________

Part - I (5 points)

Create a program that asks the user for a temperature in Fahrenheit, and then prints the temperature in Celsius. The formula for the conversion is:

C = 5.0/9.0 * (F – 32)

where C is the temperature in Celsius and F is the temperature in Fahrenheit.

Sample run:

Enter temperature in Fahrenheit: 32

The temperature in Celsius: 0.0

Sample run:

Enter temperature in Fahrenheit: 72

The temperature in Celsius: 22.2222222222

____________________________________________________________________________________________________

Part - II (5 points)

Create a new program that will ask the user for the information needed to find the area of a trapezoid, and then print the area. The formula for the area of a trapezoid is:

A = ½ * (x1 + x2) * h

where A is the area, h is the height, and x1 and x2 are the top and bottom base of the trapezoid.

Sample run:

Area of a trapezoid

Enter the height of the trapezoid: 5

Enter the length of the bottom base: 10

Enter the length of the top base: 7 

The area is: 42.5 '''



# Anthony Tolbert - Assignment 1
#  Part 1

deg_f =  int(input('What is the temperature in Fahrenheit? '))

# formula to convert Fahrenheit to Celsius: 5.0/9.0 times (degrees fahrenheit minus 32)
deg_c = 5.0/9.0 * (deg_f - 32)

print(deg_f, " degrees Fahrenheit is", deg_c, " degrees Celsius.")


# Anthony Tolbert - Assignment 1
#  Part 2

height = int(input('Enter the height of the trapezoid: '))
bottom_base = int(input('Enter the length of the bottom base: '))
top_base = int(input('Enter the length of the top base: '))

#formula to find area of trapezoid: area = 1/2 times (x1 + x2) * height
area = 1/2 * (bottom_base + top_base) * height

print('The area is ', area, )

