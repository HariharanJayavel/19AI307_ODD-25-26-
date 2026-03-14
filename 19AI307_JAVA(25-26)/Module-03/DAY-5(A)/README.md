# Ex.No:3(E) INNER CLASS

## QUESTION:
Write a Java program to create an inner class and access it from the outer class.


## AIM:
To write a Java program that demonstrates the use of an Inner Class and how it can be accessed from the Outer Class

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create an outer class.
4. Inside the outer class, declare and define an inner class.
5. Create an object of the outer class.
6. Using the outer class object, create an object of the inner class.
7. Call a method of the inner class through its object.
8. Display the output.
9. Stop the program.

## PROGRAM:
 ```
/*
Program to implement a InnerClass using Java
Developed by: HARIHARAN J
RegisterNumber:212223240047
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class OuterClass 
{
    class InnerClass
    {
        void displayMessage(String name)
        {
            System.out.println("Hello, " + name + "! This message is from the Inner Class.");
        }
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String name = sc.nextLine();
        OuterClass outer = new OuterClass();          
        OuterClass.InnerClass inner = outer.new InnerClass(); 
        inner.displayMessage(name); 
    }
}
```
## OUTPUT:

![alt text](image.png)

## RESULT:
Thus, the Java program to implement an Inner Class and access it from the Outer Class was successfully executed.




