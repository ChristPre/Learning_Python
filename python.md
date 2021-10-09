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

