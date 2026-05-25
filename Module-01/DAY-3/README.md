# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check 101 is positive or negative number.

## ALGORITHM :
1.	Start the program.
2.	Import the "Scanner" class from the "java.util" package.
3.	Define the main class named "Demo"
4.	Create a Scanner object sc to read input from the user.
5.	Read an integer input from the user and store it in variable "num"
6.	Check if num is less than 0: a) If true, print num + " is Negative".
b) Else, print num + " is Positive".
7. End the program.

## PROGRAM:
```
Program to implement control statements using Java
Developed by: THARUN DANIEL Y
RegisterNumber: 212224050054
```

## Sourcecode.java:

```
import java.util.Scanner;

public class Demo
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int num=sc.nextInt();
        if (num<0)
        {
            System.out.println(num+ " is Negative");
        }
        else
        {
        System.out.println(num+ " is Positive");
        }
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/dbfa6096-5b0b-4ece-854e-974e4335023e)


## RESULT:
Thus, the Java program to check 101 is positive or negative number was created successfully.

