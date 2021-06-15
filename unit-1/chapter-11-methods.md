# Methods
* **Gotchas:**
A little caveat before we continue. Since we have not encountered C# classes at this point, we will be working within the MainClass in your replit IDE, which limits us to working with static methods at this point. Static methods belong to the class they are created in, which in this chapter will be the MainClass.

When we learn about classes, we will learn about instance methods and be able to compare and contrast them to static methods. We will also be able to see a more usages and behaviors of static methods in a non-static environment.

A wonderful collection of static methods comes from the Math class. The documentation can be found here, and an appendix of methods can be found here.
## Introduction
### What is a Method?
* `Method`: are reusable, callable, and customizable piece of code
* `Methods` are meant to be small concise and perform a single task
* When talking about `methods` you will hear developers also call them `functions`
  * Whereas `methods` are part of a class
  * `Functions` are not
  * It is common to refer to a `method` as a `function` and vice versa
* We have been utilizing `method` without fully realizing it:
* `Console.WriteLine()`
* `Int32.Parse()`
* `GetType`


* We work with methods in the following way:
1. Type the method's name:
   * `WriteLine`
2. We then invoke or call it by following its name with parentheses:
   * `WriteLine()`
   * Then executes the method and cause it to perform its action
```C#
Console.WriteLine("Hello World");

//Outputs: Hello World
```
* The beauty of utilizing `methods` is that we are able to make our code reusable
* Also we can perform a task without having to worry about the broader actions it take
  * Take for instance `Console.WriteLine` right now you really do not have to worry about what `Console` is or how it functions
  * But you do know if you utilize it `WriteLine` method it will print whatever you pass to it to the console
  * Basically `WriteLine` is a prepackaged action (ie: method) that you have access to whenever you would like
* This concept of prepackaging our code to make it reusable is called `encapsulation`
  * `Encapsulation` is one of the four pillars of Object Oriented Programming
* 

## Method Signatures and Calls
### Method Signatures
### Creating a Method
#### Method Calls
### Invoking the Method
## Using Methods
### return vs. void Methods
### Parameters and Arguments
### Named and Optional Arguments
#### Named Arguments
#### Optional Arguments
## Recursive Methods
### FactorialRecursive A Recursive Example
### FactorialLoop A Loop Example
### Recursion or Loops?
## Scope
### Class Level Scope
### Method Level Scope
### Block Level Scope

## Whats Next
This section tell the lead instructor, teaching assistants, and students what to expect next.

1. First, student will need to complete (In this order):
   1. [Exercises: Methods](https://education.launchcode.org/intro-to-programming-csharp/chapters/methods/exercises.html)
   2. [Studio: Methods](https://education.launchcode.org/intro-to-programming-csharp/chapters/methods/studio.html)
2. Then students should read [Chapter 12: Classes, Objects, and Math Class](https://education.launchcode.org/intro-to-programming-csharp/chapters/classes-objects-math/index.html)
3. Then students will sit for [Chapter 12's Lecture](./chapter-12-classes-objects-and-math-class.md)