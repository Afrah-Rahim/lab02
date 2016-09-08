# Lab 02 -- Chapter 01

## Define the followint terms:
* object: State or behavior (instance) of a class.
* class: blueprint (code) that defines how to create an object.
* instance: Specific realization pf any object.
* method: A collection of statements in a class, that are used to manipulate (mutators) or access (accessors) information from an object of that class. (behaves like a function)
* signature: method name and type of its parameters i.e. the following signature changes the size of the instance 'box' of class 'Box' and does not give an output.
'''''
* void changeSize (Box box)
'''''
* parameter: an input of the method
* type: defines what values the parameter is allowed to be. 
* state: set of values describing an object.
* source code: collection of commands that compiles to create an executable program.
* return value: Output of a method.
* compiler: transforms source code into computer language (forces the computer to read the instructions).

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)

## What are the types of the following values?

* 0: int, double
* "hello": String
* 101 : int, double
* -1 : int, double
* true: boolean
* "33": string
* 3.1415:  double

## What would you have to do to add a new field, for example one called name, to a circle object?
'''
private String name;
'''
## Write the header for a method named send that has one parameter of type String, and does not return a value.
'''
public void send (String var1) 
'''
  
## Write the header for a method named average that has two parameters, both of type int, and returns an int value.
'''
public int Average (int v1, int v2)
'''
## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.
The book is an object of class Books. 

## Can an object have several different classes? Discuss.
No
