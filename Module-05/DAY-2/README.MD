# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To Create a java program to display the value of area of triangle get the radius and height value as input and use tightly encapsulated class.

## ALGORITHM :
1.	Start the program.
2.	Define `Triangle` class:
-	a) Private variables `width` and `height`
-	b) `setWidth(int w)` and `setHeight(int h)` methods to set values
-	c) `getVolume()` method:
- i) Calculate and print area
3.	In `Main` class `main` method:
-	a) Use `Scanner` to read `radius` and `height`
-	b) Create `Triangle` object, set values, and call `getArea()`
4.	End

## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by: DEEPIKA S
RegisterNumber: 212222230028 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class SetAndGet {
 
 private int w;
 private int h;


public int getWidth() {
 return w;
}

public void setWidth(int w) {
 this.w = w;
}

public int getHeight() {
 return h;
}

public void setHeight(int h) {
 this.h = h;
}


public static void main(String args[]){
 Scanner sc=new Scanner(System.in);
 SetAndGet obj = new SetAndGet();
 int s1=sc.nextInt();
 int s2=sc.nextInt();
 
 obj.setWidth(s1);
 obj.setHeight(s2);
 System.out.println(obj.getWidth() * obj.getHeight());

}


}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/97aed7f4-ff6f-4723-a100-ee4c84c03230)

## RESULT:
Thus a java program to display the value of area of triangle get the width and height value as input and use tightly encapsulated class was executed successfully.


