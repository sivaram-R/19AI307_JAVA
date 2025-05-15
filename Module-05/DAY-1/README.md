# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To Create a java program to display name and location of the vehicle and use the encapsulation concepts

## ALGORITHM :
1.  Start the program
2.	Define class `Employee`:
-	a) Declare two private `String` variables: `name1` and `name2`
-	b) Define `setname(String n1)` method to set `name1` to `n1`
-	c) Define `setname2(String n2)` method to set `name2` to `n2`
-	d) Define `get1()` method to return `name1`
-	e) Define `get2()` method to return `name2`
3.	Define `Main` class with `main` method:
-	a) Create `Scanner` object `sc` for input
-	b) Read `name1` and `name2` from user input
-	c) Create ` Employee ` object `hl`
-	d) Use `hl.setname(name1)` and `hl.setname2(name2)` to set the names
-	e) Print the values of `hl.get1()` and `hl.get2()`
4.	End

## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: DEEPIKA S
RegisterNumber: 212222230028 
*/
```

## Sourcecode.java:
```
import java.util.*;
class vehicle {
 private String vName;
 private String vlocation;
 public String getvName() {
  return vName;
 }
 public void setvName(String vName) {
  this.vName = vName;
 }
 public String getLocation() {
  return vlocation;
 }
 public void setLocation(String vlocation) {
  this.vlocation = vlocation;
 }
}

public class EmployeMain {
 public static void main(String[] args) {
    Scanner sc=new Scanner(System.in);
  vehicle employee = new vehicle();
  employee.setvName(sc.nextLine());
  employee.setLocation(sc.nextLine());
  System.out.println(employee.getvName());
  System.out.println(employee.getLocation());
 }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/96f1a565-1508-431c-8bb2-0e108ce13dd3)


## RESULT:
Thus , the  java program to display name and location of the vehicle and use the encapsulation concepts executed successfully.
