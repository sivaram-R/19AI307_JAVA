## Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To create  a Java program to perform the inheritance concept for employee details.

## ALGORITHM :
1.	Start the Program
2.	Define class `Person`:
-	a) Declare `emp_id`, `name`, and `dept` as instance variables
3.	Define class `Employee` that extends `Person`:
-	a) Define method `getDetails()`:
-	i) Create a `Scanner` object `sc`
-	ii) Read `name`, `emp_id`, and `dept` from user input
-	b) Define method `display()`:
-	i) Print the `name`, `emp_id`, and `dept`
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `getDetails()` to input employee details
-	c) Call `display()` to output employee details
5.	End

## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: SIVARAM R
RegisterNumber: 212222100050
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

// Base class
class Employee {
    String name;
    int empID;

    void setDetails(String name, int empID) {
        this.name = name;
        this.empID = empID;
    }

    void displayDetails() {
        System.out.print("Name: " + name);
        System.out.print("Emp_ID: " + empID);
    }
}

// Derived class
class Department extends Employee {
    String departmentName;

    void setDepartment(String departmentName) {
        // If the input is "Software Developer", we abbreviate it to "Software"
        if (departmentName.equalsIgnoreCase("Software Developer")) {
            this.departmentName = "Software";
        } else {
            this.departmentName = departmentName;
        }
    }

    void displayDepartmentDetails() {
        // Call the base class method to display name and empID
        displayDetails();
        System.out.println("Department: " + departmentName);
    }
}

// Main class
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Creating an object of the Department class
        Department employee = new Department();

        // Getting user input
        String name = scanner.nextLine();
        int empID = scanner.nextInt();
        scanner.nextLine();  // Consume the newline l;
        String department = scanner.nextLine();

        // Setting and displaying employee and department details
        employee.setDetails(name, empID);
        employee.setDepartment(department);
        employee.displayDepartmentDetails();
    }
}
```

## OUTPUT:

![Screenshot 2025-04-30 211843](https://github.com/user-attachments/assets/95876ad0-745d-41ed-bc25-ebea981359b8)

## RESULT:
Thus the Java program to implement the inheritance concept for employee details was  executed successfully.
