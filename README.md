**Encapsulation:**
In this lab, we will demonstrate Encapsulation in the Java language. By the end of this lab, learners will be able to use Encapsulation.
Introduction to Encapsulation in Java: 
Encapsulation refers to hiding the class variable from other classes and giving access to them only through methods (setters and getters).
Encapsulation in Java means binding the data (variables) with the code (methods – setters and getters). The below diagram depicts Encapsulation in Java.

Class Variables (in the example: height, weight, and bmi) are declared private; hence, they are not visible to other classes.
For each variable, there is a setter and getter method, which sets a value to the variable and gets the variable's value, respectively.
Example: For variable height, setter method is setHeight() and getter method is getHeight().
Setter and Getter methods are public; hence, they are visible to other classes.

A Program Example:
Create a class named HumanBeing with two constructors: class variables (weight, height, and bmi) and setter and getter methods.


**Guided LAB - 303.9.2 - Basic Inheritance Example**
Introduction
The process by which one class acquires the properties (data members) and functionalities (methods) of another class is called inheritance. The aim of inheritance is to provide the reusability of code so that a class has to write only the unique features, and the rest of the common properties and functionalities can be extended from the other class.
Lab Overview: 
In this lab, we will explore and demonstrate Java Inheritance.
Learning Objective:
By the end of this lab, Learners will be able to use Inheritance in Java.
Instruction:
Child Class:
The class that extends the features of another class is known as a child class, subclass, or derived class.
Parent Class:
The class whose properties and functionalities are used (inherited) by another class is known as the parent class, superclass, or base class.
In this lab, we have a base class, “Doctor,” and a subclass, “Surgeon.”


Step 1: Create a Java project named “inheritanceDemo.”
Step 2: Create a class named Doctor, and add the code below.
Step 3: Create a class named Surgeon, and add the code below.
Surgeon.java class
Step 4: Create a class named Hospital. In this class, we will create a main() method.
 Hospital.java class
Step 5: Run your Java Project.


