# Lab 02 -- Chapter 01

## Define the followint terms:
* object,an object is an instance of a class
* class, blueprint from which induvidual objects are created
* instance,an object of the class
* method,creates functionality; acceses or mutates
* signature,method name and the number and type of its parameters
* parameter,parameters are variables
* type,set of data that have predefined characteristics 
* state,conditions in which objects exist
* source code,instructions a user uses to build a program
* return value,
* compiler, special program that processes statements written in a particular programming language and turns them into machine language or "code" that a computer's processor uses.

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)

## What are the types of the following values?

* 0 int
* "hello" string
* 101 short
* -1 long
* true boolean
* "33" string
* 3.1415 double

## What would you have to do to add a new field, for example one called name, to a circle object?
String name; 
## Write the header for a method named send that has one parameter of type String, and does not return a value.
String send () {
  }
## Write the header for a method named average that has two parameters, both of type int, and returns an int value.
int Average (int total) {
int value = total / 2;
return value;
## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.
public class BetweenTheWorldandMe
{ int BookPrice = 18;
String Title = "Between the World & Me";
}
## Can an object have several different classes? Discuss.
No, it can implement multiple interfaces, and it can subclass a class with multiple superclasses, but it cannot be more than one object at a time.
