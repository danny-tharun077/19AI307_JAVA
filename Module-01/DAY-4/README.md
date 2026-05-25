# Ex.No:1(D) USER DEFINED METHOD.

## AIM:
To create a Java program to print area of Trapezium by defining instance method and local variable.[Class Name is ‘Area’ function name is ‘calculateArea()’  and return type of function is ’double’].

## ALGORITHM :

1.	Start the program.
2.	Define a class named 'Area'
3.	Declare a public method named 'calculateArea' with no parameters
4.	Inside the 'calculateArea' method:
a) Prompt and read a double value from the user and store it in variable 'b1' (base 1)
b)	Prompt and read a double value from the user and store it in variable 'b2' (base 2)
c)	Prompt and read a double value from the user and store it in variable 'h' (height)
d) Calculate the area using the formula 0.5 * h * (b1 + b2) and store the result in variable 'area'
e)	Return the calculated 'area'
6.	Define the 'main' method as 'static'
7.	Inside the 'main' method:
a)	Create an instance of the 'Area' class called 'obj'
b)	Call the 'calculateArea' method on the 'obj' object and store the result in a double variable 'area'
8. Print "Area of Trapezium is " followed by the value of 'area'
9. End the program.


## PROGRAM:
```
Program to implement a User Defined Method using Java
Developed by: SATHYAA R
RegisterNumber: 212223100052
```

## Sourcecode.java:

```
import java.util.*;
public class Area 
{
    public double calculateArea() 
    {
        Scanner sc = new Scanner(System.in);
        double b1 = sc.nextDouble();
        double b2 = sc.nextDouble();
        double h = sc.nextDouble();
        double area = 0.5 * h * (b1 + b2);
        return area;
    }
    public static void main(String[] args) 
    {
        Area obj=new Area();
        double area=obj.calculateArea();
        System.out.println("Area of Trapezium is "+area);
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/defb1599-4df7-4035-94bc-243d0bd7e858)


## RESULT:
Thus, the Java program to print area of Trapezium by defining instance method and local variable was created successfully.

