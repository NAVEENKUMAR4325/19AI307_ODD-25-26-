# Ex.No:2(B) METHODS

## QUESTION:
Write a method int square(int number) that returns the square of a given number.

## AIM:
To write a method int square(int number) that returns the square of a given number.


## ALGORITHM :
1.Create a method named square that takes an integer parameter number
2.Inside the method, calculate the square by multiplying the number by itself
3.Return the calculated square value
4.In the main method, test the square method with sample inputs





## PROGRAM:
 ```
/*
Program to implement a Methods using Java
Developed by: Naveen Kumar E
RegisterNumber:  212222220029
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class MathOps {

    public int square(int number) {
        return number * number;
    }

    public static void main(String[] args) {
        MathOps ops = new MathOps();
        Scanner scanner = new Scanner(System.in);
        
        int input = scanner.nextInt();
        int result = ops.square(input);
        
        System.out.println(result);
        
        scanner.close();
    }
}
```






## OUTPUT:
<img width="438" height="144" alt="image" src="https://github.com/user-attachments/assets/2fb7b617-6e4b-405c-aa70-86a35fc10d5e" />



## RESULT:
The square method was successfully implemented and returns the correct square value for any given integer input.


