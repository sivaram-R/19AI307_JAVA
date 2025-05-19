# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find sum of natural numbers using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :
1.	Start the Program
2.	Define class `A`:
-	a) Declare integer `n` and initialize `sum` to 1
-	b) Define method `factorial(int n)`:
-	i) Set `this.n = n`
-	ii) Use a loop from 1 to `n` to calculate sum
-	iii) Print "Sum is:" followed by `sum`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integer `n`
-	b) Create an `A` object and call `sum(n)`
4.	End

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: SIVARAM R
RegisterNumber: 212222100050
*/
```

## Sourcecode.java:
```
import java.util.*;
import java.util.Scanner;
class s1{
    void Oddsum(int number)
    {
	int i = 1, sum = 0;
	while(i <= number) 
        {
            sum += i;
            i++;
        }
 
    System.out.println("Sum = " + sum);
    } 

 
}

public class Odd_sum{
	public static void main(String args[])
	{
	   int number;  
      
      Scanner sc = new Scanner(System.in);
      number=sc.nextInt();
      s1 obj=new s1();
      obj.Oddsum(number);
	}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/d2bdb78c-2179-410d-bafb-bc39849f3944)


## RESULT:
Thus the java program to find sum of natural number using class and object concepts and apply the has-a relationship was executed successfully.
