# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java Program to implement Method Local Inner Class.

## ALGORITHM :
1.  Start the Program.
2.	Define outer class `name`:
-	a) Declare `String name` and initialize it to "Johnson"
-	b) Define inner class `inner`:
- i) Define method `display()` that prints "Name given in Outer Class is " followed by `name`
3.	In the `main` method of `name` class:
-	a) Create an instance `obj` of the `name` class
-	b) Create an instance `obj2` of the inner class `inner` using `obj`
-	c) Call `display()` on `obj2` to print the outer class name
4.	End

## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by: DEEPIKA S
RegisterNumber: 212222230028
*/
```

## Sourcecode.java:
```
class MethodLocal
{
    public String value = "Name given in Outer Class is Johnson";
    public void display()
    {
        class Inner
        {
            public void print()
            {
                System.out.println(value);
            }
        }
        Inner obj1 = new Inner();
        obj1.print();
    }
}
public class Main
{
    public static void main(String[]args)
    {
        MethodLocal obj = new MethodLocal();
        obj.display();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/54f24f87-d30a-44de-be17-751733337eae)


## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.
