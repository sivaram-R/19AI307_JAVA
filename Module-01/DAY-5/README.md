# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program to print student details (name and age), where age is the same for all students. Use a static variable to represent the age and demonstrate its use in accessing a shared value across all class objects

## ALGORITHM :
1.	Start the program.
2.	Create a class named Student.
3.	Declare a static variable age in the Student class.
4.	Declare an instance variable name.
5.	Create a constructor to initialize the student's name.
6.	Define a method displayDetails() to print the student's name and age.
7.	In the main method:
I.	Assign a value to the static variable age.
II.	Create multiple Student objects with different names.
III.	Call the displayDetails() method for each student.
8.	End the program.

## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: SIVARAM R
RegisterNumber: 212222100050
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class Student {
    String name;
    static int age = 18; // Static variable for age, same for all students

    // Constructor to set the student's name
    Student(String name) {
        this.name = name;
    }

    // Method to print student details
    void printDetails() {
        System.out.println("Student name: " + name + "Age: " + age);
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

       
        String name1 = scanner.nextLine();
        Student student1 = new Student(name1);

    
        String name2 = scanner.nextLine();
        Student student2 = new Student(name2);

        // Print details of both students
        student1.printDetails();
        student2.printDetails();

        scanner.close();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/2567c887-b649-4cc6-b97b-4fe76a847798)

## RESULT:
Thus, the Java program for the concept of using a static variable for shared data was correctly implemented and verified successfully. 
