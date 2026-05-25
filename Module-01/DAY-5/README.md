# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program to read the 4 numbers from the user and print the greatest number.

## ALGORITHM :

1.	Start the program.
2.	Define a class named 'Greatest'.
3.	Define the main method as 'static'.
4.	Create a 'Scanner' object to read input from the user.
5.	Read four integer values from the user and store it in variables 'n1', 'n2', 'n3' and 'n4'.
6.	Use conditional statements to compare the values:
i) If n1 is greater than n2, n3, and n4, then print "n1 is greatest".
ii) Else if n2 is greater than n1, n3, and n4, then print "n2 is greatest".
iii) Else if n3 is greater than n1, n2, and n4, then print "n3 is greatest".
iv) Else, print "n4 is greatest".
7.	End the program.


## PROGRAM:

```
Program to implement a Static Variable using Java
Developed by: THARUN DANIEL Y
RegisterNumber: 212224050054
```

## Sourcecode.java:

```
import java.util.*;
public class Greatest
{
    public static void main(String argv[])
    {
        Scanner sc=new Scanner(System.in);
        int n1=sc.nextInt();
        int n2=sc.nextInt();
        int n3=sc.nextInt();
        int n4=sc.nextInt();
        if (n1>n2 && n1>n3 && n1>n4)
        {
            System.out.println(+n1+" is greatest");
        }
        else if (n2>n1 && n2>n3 && n2>n4)
        {
            System.out.println(+n2+" is greatest");
        }
        else if (n3>n1 && n3>n2 && n3>n4)
        {
            System.out.println(+n3+" is greatest");
        }
        else
        {
            System.out.println(+n4+" is greatest");
        }
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/d4171dc8-7452-407b-a50a-6d3a941b17f5)


## RESULT:
Thus, the Java program to read the 4 numbers from the user, from that to print the greatest numbers was correctly implemented and verified successfully. 

