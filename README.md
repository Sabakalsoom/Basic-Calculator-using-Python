# Basic-Calculator-using-Python
Creating a simple calculator which can perform basic arithmetic operations like addition, subtraction, multiplication or division depending upon the user input. 

Python is a high level programming language similar to C++/Java.
It is open source and has a large community. 
it is used by a lot of companies around the world.
It is interpreted script language, good for writing quick and dirty code. 
It is object oriented. (Everything is a python object).
Different code blocks are grouped together by indentation. 
The standard library offers a plethora of very useful functions. 
Traditionally the first program you write in any programming language is "Hello World!". 

Introduce yourself to the World. 
print("Hello, world! My name is Saba Kalsoom")

There is no difference between double and single quotation marks but one needs to be consistent with the quotation marks once used.

We don’t use a semicolon in python. 
Comments in Python start with the hash character ( #) and include the whole line. You can use Ctrl + / to comment or uncomment the whole line in PyCharm. 

Variables are used to store values so we can refer to them later. A variable is like a label, and you use the ' =' symbol, known as the assignment operator, to assign a value to a variable. An assignment can be chained, e.g. a= b = 2 

a = b = 2  # This is called a "chained assignment". It assigns the value 2 to variables "a" and "b".
print("a = " + str(a))   # We'll explain the expression str(a) later in the course. For now it is used to convert the  variable "a" to a string.
print("b = " + str(b))

greetings = "greetings"
print("greetings = " + str(greetings))
greetings = "hello"
print("greetings = " + str(greetings))

a = 2
b = 2
greetings = greetings
greetings = hello



Variable names may only contain letters, digits, and/or the underscore character, and cannot start with a digit. 

Check what happens if you use a variable which is not defined yet. Try to print out an undefined name. 
 
It gives an error.

In Python, there are two main types of numbers: integers and floats. The most important difference between them is that a float is a number that has a decimal point, and an int is a number without a decimal point. 

Determine the type of the variable float_number. 
number = 9
print(type(number))   # print type of variable "number"

float_number = 9.0
print(type(float_number))

<class 'int'>
<class 'float'>

There are several built-in functions that let you convert one data type to another. These functions return a new object representing the converted value. int(x)converts x to an integer. float(x) converts x to a floating-point number. str(x) converts object x to a string representation. 

float_number = 9.0
print(float_number)
print(int(float_number))

Output:
<class 'int'>
9.0
9

Just as with any other programming language, the addition ( +), subtraction ( -), multiplication ( *), and division ( /) operators can be used with numbers. In addition Python has the power ( **) and modulo ( %) operators. 

number = 9.0        # float number

result = number/2

remainder = number%2

print("result = " + str(result))
print("remainder = " + str(remainder))

Output:
result = 4.5
remainder = 1.0

Augmented assignment is a single statement combining a binary operation and an assignment statement such as +=, -=, etc. 

Use an augmented assignment to add 5 to number and update the variable. 
number = 9.0
print("number = " + str(number))

number -= 2
print("number = " + str(number))

number += 5

print("number = " + str(number))
number = 9.0
number = 7.0
number = 12.0

Boolean is a type of value that can only be True or False. The == (equality) operator checks whether the two variables being compared are equal. 

Check whether the variable two is equal to three. 
two = 2
three = 3

is_equal = two == three

print(is_equal)

Output:
False

Python has many types of comparison operators including >=, <=, >, <, etc. All comparison operations in Python have the same priority. Comparisons yield boolean values: either True or False. Comparisons can be chained arbitrarily. 

Check whether the value of the variable three is strictly greater than the value of the variable two. 
one = 1
two = 2
three = 3

print(one < two < three)  # This chained comparison means that the (one < two) and (two < three) comparisons are performed at the same time.

is_greater = three > two
print(is_greater)

Output:
True
True

Combining two strings using the + symbol is called concatenation. 

Use the hello and world variables to get a "Hello World" string. 


hello = "Hello"
world = 'World'

hello_world = hello + ' ' +  world
print(hello_world)      # Note: you should print "Hello World"


Output:
Hello World


Python supports a string-by-number multiplication (but not the other way around!). 

Use hello to get the "hellohellohellohellohellohellohellohellohellohello"string ( "hello" repeated 10 times). 

hello = "hello"
ten_of_hellos = hello * 10
print(ten_of_hellos)

Output:
hellohellohellohellohellohellohellohellohellohello

You can access a character of a string if you know its position. For example, str[index] will yield the character at position index in the string str. 
Note that string index always starts at 0. 
Indices may also be negative numbers, to start counting from the right. Note that since -0 is the same as 0, negative indices start from -1. 

Use index operator to get "P" from "python". 
python = "Python"
print("h " + python[3])     # Note: string indexing starts with 0

p_letter = python[0]
print(p_letter)

Output:
h h
P


You can use negative numbers in the indexing operator to count characters ‘backwards’ from the end of the string. 

Use negative index to get the '!' sign from long_string 

