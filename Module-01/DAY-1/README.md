# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To Create a class named 'Student' with String variable 'dept', String variable 'name' and  and integer variable 'rollno'.
## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: THARUN DANIEL Y
RegisterNumber: 212224050054
*/

public class Student
{
    String dept,name;
    int rollno;
}

public class Main {
    public static void main(String[] args) {
        Student obj= new Student();
        obj.dept="AIML";
        obj.name="John";
        obj.rollno=15;   
        System.out.println(obj.dept+" "+obj.name+" "+obj.rollno);
    }   
} 


```



## OUTPUT:
![image](https://github.com/user-attachments/assets/43e4a7fe-a675-4d39-9d50-fe0b6130a8e8)



## RESULT:
Thus, the  class named 'Student' with String variable 'dept', String variable 'name' and  and integer variable 'rollno' was created successfully.
