# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To develop a java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuffer.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `replace`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read two strings `a` and `b` from user input
4.	Create a `StringBuffer` object `sb` initialized with string `a`
5.	Replace a the string 
6.	Print the replaced result from `sb`
7.	End

## PROGRAM:
 ```
/*
Program to implement a String Buffer using Java
Developed by: DEEPIKA S
RegisterNumber: 212222230028 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class StringBufferExample3{  
    public static void main(String args[]){ 
        Scanner sc=new Scanner(System.in);
        String str1=sc.nextLine();
        StringBuffer sb=new StringBuffer(str1);  
        sb.replace(1,3,"Java");  
        System.out.println(sb); 
}  
}  
```

## OUTPUT:

![Screenshot 2025-04-30 160051](https://github.com/user-attachments/assets/84bc5f5f-9152-4730-8676-1e252986726f)

## RESULT:
Thus the java program use append() method concatenates the given argument with this String and use stringbuffer class was executed successfully.
