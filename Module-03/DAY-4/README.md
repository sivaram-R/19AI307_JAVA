# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace.

## ALGORITHM :
1.	Start the Program
2.	Import `Scanner` and `StringTokenizer` and define class `tok`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Initialize the string `str` as "My name is Java Programming"
4.	Create a `StringTokenizer` object `token` to tokenize `str`
5.	Use a `while` loop to iterate through tokens:
-	a) Print each token using `token.nextToken()`
6.	End

## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: DEEPIKA S
RegisterNumber: 212222230028
*/
```

## Sourcecode.java:
```
import java.util.StringTokenizer;  
public class Simple{  
 public static void main(String args[]){  
   StringTokenizer st = new StringTokenizer("My name is Java Programming"," ");  
     while (st.hasMoreTokens()) {  
         System.out.println(st.nextToken());  
     }  
   }  
}  
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/47efceb1-6f9f-493d-9c2f-c4b5f77ba270)

## RESULT:
Thus the java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace was executed successfully.
