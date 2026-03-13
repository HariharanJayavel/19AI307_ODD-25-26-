# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java program to find the index of a given element in an array.

## AIM:
To write a Java program that finds the index position of a specified element from a given array.


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the size of the array from the user.
4. Create an array of the given size.
5. Read the array elements from the user and store them in the array.
6. Read the element to be searched.
7. Traverse the array and compare each element with the search element.
8. If matched, print the index position and terminate.
9. If not found, display "Element not found".
10. Stop the program.





## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: HARIHARAN J
RegisterNumber: 212223240047
*/
```

## SOURCE CODE:

```
import java.util.*;
public class Main
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int[] arr=new int[n];
        for(int i=0;i<n;i++)
        {
            arr[i]=sc.nextInt();
        }
        int key=sc.nextInt();
        int index=-1;
        for(int i=0;i<n;i++)
        {
            if(arr[i]==key)
            {
                index=i;
                break;
            }
        }
        
        if(index!=-1)
        {
            
            System.out.println(index);
        }
        else{
            System.out.println("Element not found");
        }
    }
}
```





## OUTPUT:
<img width="671" height="645" alt="image" src="https://github.com/user-attachments/assets/0de19897-6bb3-4b23-844a-f86f52d53974" />



## RESULT:
Thus, the Java program to find the index of a given element in an array was successfully executed.

