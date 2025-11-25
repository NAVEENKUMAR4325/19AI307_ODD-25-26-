# Ex.No:3(E) INNER CLASS

## QUESTION:
Write a Java program to check whether a given number is an Armstrong number using Math.pow() and the Integer wrapper class. Get input from the user.

## AIM:
To write a Java program that checks if a number is an Armstrong number using Math.pow() and Integer wrapper class.

## ALGORITHM :
1.Start the program.
2.Import the package java.util.Scanner.
3.Read a number from the user.
4.Store the original number.
5.Find the number of digits using Integer.toString().
6.Extract each digit and compute its power using Math.pow().
7.Add the calculated values to find the sum.
8.Compare the sum with the original number.
9.Display whether it is an Armstrong number.
10.Stop the program.
## PROGRAM:
 ```
/*
Program to implement a InnerClass using Java
Developed by: Naveen Kumar E
RegisterNumber: 212222220029 
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class ArmstrongCheck {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int number = sc.nextInt();

        int original = number;
        int digits = Integer.toString(number).length();
        int sum = 0;

        while (number != 0) {
            int digit = number % 10;
            sum += (int) Math.pow(digit, digits);
            number /= 10;
        }

        if (sum == original) {
            System.out.println(original + " is an Armstrong number.");
        } else {
            System.out.println(original + " is not an Armstrong number.");
        }

        sc.close();
    }
}


```

## OUTPUT:

<img width="830" height="262" alt="image" src="https://github.com/user-attachments/assets/084ae1d3-e86f-4a10-a483-b3fbc1e8e2a2" />


## RESULT:
The program to check whether a given number is an Armstrong number using Math.pow() and Integer wrapper class was successfully executed and the output was verified.

