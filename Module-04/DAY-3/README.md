# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
1.  Start the Program.
2.	Define class `College`:
-	a) Define method `display()` that prints "I am a Vehicle"
3.	Define class `Student` that extends `College`:
-	a) Override method `display()` to print "I am a Car"
-	b) Define method `print()`:
-	i) Call `super.display()` to invoke `display()` from `College` class
-	ii) Call `this.display()` to invoke `display()` from `Student` class
4.	Define `Main` class with `main` method:
-	a) Create a `Student` object `sc`
-	b) Call `sc.print()` to execute the `print()` method
5.	End

## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: SIVARAM R
RegisterNumber: 212222100050
*/
```

## Sourcecode.java:
```
// Base class Vehicle
class Vehicle {
    // Constructor for Vehicle
    Vehicle() {
        System.out.println("I am a Vehicle");
    }
}

// Derived class Car that extends Vehicle
class Car extends Vehicle {
    // Constructor for Car
    Car() {
        // Call the constructor of Vehicle
        super();
        System.out.println("I am a Car");
    }
}

// Main class to test the implementation
public class Main {
    public static void main(String[] args) {
        // Create an instance of Car
        Car car = new Car();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/403dac3b-99d9-4d93-afc2-070ee490f80b)

## RESULT:
Thus the java program for constructor chaining was executed successfully.



