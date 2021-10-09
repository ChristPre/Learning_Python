# Learning Python

## PYTHON INTRODUCTION

Python is a popular programming language.

Python can be used on a server to create web applications.

## WHAT IS PYTHON ?

Python is a popular programming language. It was created by Guido van Rossum, and released in 1991.

![70fa523c20fd1ac614d08ff9521cff3c46_scaled_v1_400](https://user-images.githubusercontent.com/76608611/136461420-d1e0b720-a611-484f-895b-e341f35d0e01.jpg)

It is used for:

- web development (server-side),
- software development,
- mathematics,
- system scripting.

## WHAT CAN PYTHON DO ?

- Python can be used on a server to create web applications.
- Python can be used alongside software to create workflows.
- Python can connect to database systems. It can also read and modify files.
- Python can be used to handle big data and perform complex mathematics.
- Python can be used for rapid prototyping, or for production-ready software development.

## WHY PYTHON ?

- Python works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc).
- Python has a simple syntax similar to the English language.
- Python has syntax that allows developers to write programs with fewer lines than some other programming languages.
- Python runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.
- Python can be treated in a procedural way, an object-oriented way or a functional way.

## GOOD TO KNOW THAT ...

- The most recent major version of Python is Python 3, which we shall be using in this tutorial. However, Python 2, although not being updated with anything other than security updates, is still quite popular.
- In this tutorial Python will be written in a text editor. It is possible to write Python in an Integrated Development Environment, such as Thonny, Pycharm, Netbeans or Eclipse which are particularly useful when managing larger collections of Python files.

## PYTHON SYNTAX COMPARED TO OTHER PROGRAMMING LANGUAGES

- Python was designed for readability, and has some similarities to the English language with influence from mathematics.
- Python uses new lines to complete a command, as opposed to other programming languages which often use semicolons or parentheses.
- Python relies on indentation, using whitespace, to define scope; such as the scope of loops, functions and classes. Other programming languages often use curly-brackets for this purpose

###### EXAMPLE 

```.py
print("Hello, Christ Précieux")

```

## PYTHON QUICKSTART

Python is an interpreted programming language, this means that as a developer you write Python (.py) files in a text editor and then put those files into the python interpreter to be executed.

The way to run a python file is like this on the command line:

> C:\Users\Your Name>python helloworld.py

Where "helloworld.py" is the name of your python file.

## PYTHON SYNTAX

Executing python syntax can be done by writing directly in the Command Line:
>>> print("Hello, World!")
Hello, World !

## PYTHON IDENTATION

Indentation refers to the spaces at the beginning of a code line.

Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.

Python uses indentation to indicate a block of code.

###### EXAMPLE

```.py
if 5 > 2:
  print("Five is greater than two!")
```
However, Python will give you an error if you skip the indentation:

```.py
if 5 > 2:
print("Five is greater than two!")
```

NB: The number of spaces is up to you as a programmer, but it has to be at least one.

```.py
if 5 > 2:
 print("Five is greater than two!") 
if 5 > 2:
        print("Five is greater than two!")
```

In order to avoid any code issue, You have to use the same number of spaces in the same block of code, otherwise Python will give you an error:

```.py
if 5 > 2:
 print("Five is greater than two!")
        print("Five is greater than two!")
```

###### Python variables

In Python, variables are created when you assign a value to it:

###### EXAMPLE

```.py
x = 5
y = "Hello, World!"

print(x)
print(y)
```

Python has no command for declaring a variable.
This will be learn more in Python Variable chapter

###### Comments

Python has commenting capability for the purpose of in-code documentation.

Comments start with a #, and Python will render the rest of the line as a comment:

```.py
# this is a comment
print("Nice to learn Python C'P!")
```

## PYTHON COMMENTS

Comments can be used to explain Python code.

Comments can be used to make the code more readable.

Comments can be used to prevent execution when testing code.

**Creating a Comment**

Comments starts with a #, and Python will ignore them:

```.py
# this is a comment
print("Python is fun!")
```

Comments can be placed at the end of a line, and Python will ignore the rest of the line:

```.py
print("Python is fun!") # this is a comment
```

A comment does not have to be text that explains the code, it can also be used to prevent Python from executing code:

```.py
#print("Hello, World!")
print("Cheers, Homie!")
```

###### Multi Line Comments

Python does not really have a syntax for multi line comments.

To add a multiline comment you could insert a # for each line:

```.py
#This is a comment
#written in
#more than just one line
print("Hello, World!")
```

Or, not quite as intended, you can use a multiline string.

Since Python will ignore string literals that are not assigned to a variable, you can add a multiline string (triple quotes) in your code, and place your comment inside it:

```.py
"""
This is a comment
written in
more than just one line
"""
print("Hello, World!")
```

As long as the string is not assigned to a variable, Python will read the code, but then ignore it, and you have made a multiline comment.

## PYTHON VARIABLE

**Variable**

Variables are containers for storing data values.

**Creating Variables**

Python has no command for declaring a variable.
A variable is created the moment you first assign a value to it.

```.py
x = 5
y = "John"
print(x)
print(y)
```

Variables do not need to be declared with any particular type, and can even change type after they have been set.

```.py
x = 4       # x is of type int
x = "Sally" # x is now of type str
print(x)
```

**Casting**

If you want to specify the data type of a variable, this can be done with casting.

```.py
x = str(3)    # x will be '3'
y = int(3)    # y will be 3
z = float(3)  # z will be 3.0
```

**Get the type**

You can get the data type of a variable with the type() function.

```.py
x = 5
y = "John"
print(type(x))
print(type(y))
```

**Single or Double Quotes?**

String variables can be declared either by using single or double quotes:

```.py
x = "John"
# is the same as
x = 'John'
```

**Case-Sensitive**

Variable names are case-sensitive.

```.py
a = 4
A = "Sally"
#A will not overwrite a
#This will create two variables:
```

**Variable Names**

A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:

- A variable name must start with a letter or the underscore character
- A variable name cannot start with a number
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variable names are case-sensitive (age, Age and AGE are three different variables)

###### EXAMPLE

Legal variable names:

```.py
myvar = "John"
my_var = "John"
_my_var = "John"
myVar = "John"
MYVAR = "John"
myvar2 = "John"
```

Illegal variable names:

```.py
2myvar = "John"
my-var = "John"
my var = "John"
```

**NB: Remember that variable names are case-sensitive**

**Multi Words Variable Names**

Variable names with more than one word can be difficult to read.

There are several techniques you can use to make them more readable:

**Camel**

Each word, except the first, starts with a capital letter:

```.py
myVariableName = "John"
```

**Pascal Case**

Each word starts with a capital letter:

```.py
MyVariableName = "John"
```

**Snake Case**

Each word is separated by an underscore character:

```.py
my_variable_name = "John"
```

**Assign Multiple Values**

**Many Values to Multiple Variables**

Python allows you to assign values to multiple variables in one line:

```.py
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)
```

**Note:** Make sure the number of variables matches the number of values, or else you will get an error.

**One Value to Multiple Variables**

And you can assign the same value to multiple variables in one line:

```.py
x = y = z = "Orange"
print(x)
print(y)
print(z)
```

**Unpack a Collection**

If you have a collection of values in a list, tuple etc. Python allows you extract the values into variables. This is called unpacking.

Unpack a list:

```.py
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)
```

**Output Variables**

The Python print statement is often used to output variables.

To combine both text and a variable, Python uses the + character:

```.py
x = "awesome"
print("Python is " + x)
```

You can also use the + character to add a variable to another variable:

```.py
x = "Python is "
y = "awesome"
z =  x + y
print(z)
```

For numbers, the + character works as a mathematical operator:

```.py
x = 5
y = 10
print(x + y)
```

If you try to combine a string and a number, Python will give you an error:

```.py
x = 5
y = "John"
print(x + y)
```

**Global Variables**

Variables that are created outside of a function (as in all of the examples above) are known as global variables.

Global variables can be used by everyone, both inside of functions and outside.

###### EXAMPLE

Create a variable outside of a function, and use it inside the function

```.py
x = "awesome"

def myfunc():
  print("Python is " + x)

myfunc()
```

If you create a variable with the same name inside a function, this variable will be local, and can only be used inside the function. The global variable with the same name will remain as it was, global and with the original value.

**eg:** Create a variable inside a function, with the same name as the global variable

```.py
x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()

print("Python is " + x)
```

**The global Keyword**

Normally, when you create a variable inside a function, that variable is local, and can only be used inside that function.

To create a global variable inside a function, you can use the global keyword.

**example**

If you use the global keyword, the variable belongs to the global scope:

```.py
def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)
```

Also, use the global keyword if you want to change a global variable inside a function.

**example**

To change the value of a global variable inside a function, refer to the variable by using the global keyword:

```.py
x = "awesome"

def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)
```

## PYTHON DATA TYPES

**Built-in Data Types**

In programming, data type is an important concept.

Variables can store data of different types, and different types can do different things.

Python has the following data types built-in by default, in these categories:

Text Type:	    str
Numeric Types:	int, float, complex
Sequence Types:	list, tuple, range
Mapping Type:	  dict
Set Types:	    set, frozenset
Boolean Type:	  bool
Binary Types:	  bytes, bytearray, memoryview

**Getting the Data Type**

You can get the data type of any object by using the type() function:

```.py
x = 5
print(type(x))

#output
<class 'int'>
```

**Setting the Data Type**

In Python, the data type is set when you assign a value to a variable:

| example                                      	| data types 	|
|----------------------------------------------	|------------	|
| x = "Hello World"                            	| str        	|
| x = 20                                       	| int        	|
| x = 20.5                                     	| float      	|
| x = 1j                                       	| complex    	|
| x = ["apple", "banana", "cherry"]            	| list       	|
| x = ("apple", "banana", "cherry")            	| tuple      	|
| x = range(6)                                 	| range      	|
| x = {"name" : "John", "age" : 36}            	| dict       	|
| x = {"apple", "banana", "cherry"}            	| set        	|
| x = frozenset({"apple", "banana", "cherry"}) 	| frozenset  	|
| x = True                                     	| bool       	|
| x = b"Hello"                                 	| bytes      	|
| x = bytearray(5)                             	| bytearray  	|
| x = memoryview(bytes(5))                     	| memoryview 	|


**Setting the Specific Data Type**

If you want to specify the data type, you can use the following constructor functions:

| Example                                      	| data type  	|
|----------------------------------------------	|------------	|
| x = str("Hello World")                       	| str        	|
| x = int(20)                                  	| int        	|
| x = float(20.5)                              	| float      	|
| x = complex(1j)                              	| complex    	|
| x = list(("apple", "banana", "cherry"))      	| list       	|
| x = tuple(("apple", "banana", "cherry"))     	| tuple      	|
| x = range(6)                                 	| range      	|
| x = dict(name="John", age=36)                	| dict       	|
| x = set(("apple", "banana", "cherry"))       	| set        	|
| x = frozenset(("apple", "banana", "cherry")) 	| frozenset  	|
| x = bool(5)                                  	| bool       	|
| x = bytes(5)                                 	| bytes      	|
| x = bytearray(5)                             	| bytearray  	|
| x = memoryview(bytes(5))                     	| memoryview 	|


## PYTHON NUMBERS

There are three numeric types in Python:

- int
- float 
- complex

Variables of numeric types are created when you assign a value to them:

```.py
x = 1    # int
y = 2.8  # float
z = 1j   # complex
```

To verify the type of any object in Python, use the type() function:

```.py
print(type(x))
print(type(y))
print(type(z))
```

**Int**

Int, or integer, is a whole number, positive or negative, without decimals, of unlimited length.

integers:

```.py
x = 1
y = 35656222554887711
z = -3255522

print(type(x))
print(type(y))
print(type(z))
```

**Float**

Float, or "floating point number" is a number, positive or negative, containing one or more decimals.

```.py
x = 1.10
y = 1.0
z = -35.59

print(type(x))
print(type(y))
print(type(z))
```
Float can also be scientific numbers with an "e" to indicate the power of 10.

```.py
x = 35e3
y = 12E4
z = -87.7e100

print(type(x))
print(type(y))
print(type(z))
```

**Complex**

Complex numbers are written with a "j" as the imaginary part:

```.py
x = 3+5j
y = 5j
z = -5j

print(type(x))
print(type(y))
print(type(z))
```

**Type Conversion**

You can convert from one type to another with the int(), float(), and complex() methods:

Convert from one type to another:

```.py
x = 1    # int
y = 2.8  # float
z = 1j   # complex

#convert from int to float:
a = float(x)

#convert from float to int:
b = int(y)

#convert from int to complex:
c = complex(x)

print(a)
print(b)
print(c)

print(type(a))
print(type(b))
print(type(c))
```

**Note:** You cannot convert complex numbers into another number type.

**Random Number**

Python does not have a random() function to make a random number, but Python has a built-in module called random that can be used to make random numbers:

Import the random module, and display a random number between 1 and 9:

```.py
import random

print(random.randrange(1, 10))
```

## PYTHON CASTING

**Specify a Variable Type**

There may be times when you want to specify a type on to a variable. This can be done with casting. Python is an object-orientated language, and as such it uses classes to define data types, including its primitive types.

Casting in python is therefore done using constructor functions:

- int() - constructs an integer number from an integer literal, a float literal (by removing all decimals), or a string literal (providing the string represents a whole number)
- float() - constructs a float number from an integer literal, a float literal or a string literal (providing the string represents a float or an integer)
- str() - constructs a string from a wide variety of data types, including strings, integer literals and float literals

***Integers**

```.py
x = int(1)   # x will be 1
y = int(2.8) # y will be 2
z = int("3") # z will be 3
```

***Floats***

```.py
x = float(1)     # x will be 1.0
y = float(2.8)   # y will be 2.8
z = float("3")   # z will be 3.0
w = float("4.2") # w will be 4.2
```

***Strings***

```.py
x = str("s1") # x will be 's1'
y = str(2)    # y will be '2'
z = str(3.0)  # z will be '3.0'
```

## PYTHON STRINGS

1. STRINGS 

Strings in python are surrounded by either single quotation marks, or double quotation marks.

'hello' is the same as "hello".

You can display a string literal with the print() function:

```.py
print("Hello")
print('Hello')
```

**Assign String to a Variable**

Assigning a string to a variable is done with the variable name followed by an equal sign and the string:

```.py
a = "Hello"
print(a)
```

**Multiline Strings**

You can assign a multiline string to a variable by using three quotes:

You can use three double quotes:

```.py
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)
```

Or three single quotes:

```.py
a = '''Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.'''
print(a)
```

Note: in the result, the line breaks are inserted at the same position as in the code.

**Strings are Arrays**

Like many other popular programming languages, strings in Python are arrays of bytes representing unicode characters.

However, Python does not have a character data type, a single character is simply a string with a length of 1.

Square brackets can be used to access elements of the string.

Get the character at position 1 (remember that the first character has the position 0):

```.py
a = "Hello, World!"
print(a[1])
```

**Looping Through a String**

Since strings are arrays, we can loop through the characters in a string, with a for loop.

Loop through the letters in the word "banana":

```.py
for x in "banana":
  print(x)
```

**String Length**

To get the length of a string, use the len() function.

The len() function returns the length of a string:

```.py
a = "Hello, World!"
print(len(a))
```

**Check String**

To check if a certain phrase or character is present in a string, we can use the keyword in.

Check if "free" is present in the following text:

```.py
txt = "The best things in life are free!"
print("free" in txt)
```

Use it in an if statement:

Print only if "free" is present:

```.py
txt = "The best things in life are free!"
if "free" in txt:
  print("Yes, 'free' is present.")
```

**Check if NOT**

To check if a certain phrase or character is NOT present in a string, we can use the keyword not in.

Check if "expensive" is NOT present in the following text:

```.py
txt = "The best things in life are free!"
print("expensive" not in txt)
```

Use it in an if statement:
print only if "expensive" is NOT present:

```.py
txt = "The best things in life are free!"
if "expensive" not in txt:
  print("No, 'expensive' is NOT present.")
```

2. Slicing Strings

**Slicing**

You can return a range of characters by using the slice syntax.

Specify the start index and the end index, separated by a colon, to return a part of the string.

Get the characters from position 2 to position 5 (not included):

```.py
b = "Hello, World!"
print(b[2:5])
```

**Note:** The first character has index 0.

**Slice From the Start**

By leaving out the start index, the range will start at the first character:

Get the characters from the start to position 5 (not included):

```.py
b = "Hello, World!"
print(b[:5])
```

**Slice To the End**

By leaving out the end index, the range will go to the end:

Get the characters from position 2, and all the way to the end:

```.py
b = "Hello, World!"
print(b[2:])
```

**Negative Indexing**

Use negative indexes to start the slice from the end of the string:

Get the characters:

From: "o" in "World!" (position -5)

To, but not included: "d" in "World!" (position -2):

```.py
b = "Hello, World!"
print(b[-5:-2])
```

3. Modify Strings

Python has a set of built-in methods that you can use on strings.

**Upper Case**

The upper() method returns the string in upper case:

```.py
a = "Hello, World!"
print(a.upper())
```

**Lower Case**

The lower() method returns the string in lower case:

```.py
a = "Hello, World!"
print(a.lower())
```

**Remove Whitespace**

Whitespace is the space before and/or after the actual text, and very often you want to remove this space.

The strip() method removes any whitespace from the beginning or the end:

```.py
a = " Hello, World! "
print(a.strip()) # returns "Hello, World!"
```

**Replace String**

The replace() method replaces a string with another string:

```.py
a = "Hello, World!"
print(a.replace("H", "J"))
```

**Split String**

The split() method returns a list where the text between the specified separator becomes the list items.

The split() method splits the string into substrings if it finds instances of the separator:

```.py
a = "Hello, World!"
print(a.split(",")) # returns ['Hello', ' World!']
```

