# Ex.No:3(F) WRAPPER CLASS

## QUESTION:
Write a Java program to create an enum Season with values WINTER, SPRING, SUMMER, and FALL. Use a switch statement to display a custom message based on the current season entered by the user.

## AIM:
To write a Java program that reads a season from the user, converts it into an enum type, and displays a corresponding message using a switch statement.

## ALGORITHM :
1.Start the program.
2.Import the package java.util.Scanner.
3.Define an enum named Season with four values.
4.Read input from the user.
5.Convert the input to uppercase and map it to the enum using valueOf().
6.Use a switch statement to display the appropriate message.
7.Display the output.
8.Stop the program.


## PROGRAM:
 ```
/*
Program to implement a Wrapper Class using Java
Developed by: Naveen Kumar E
RegisterNumber: 212222220029
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

enum Season {
    WINTER, SPRING, SUMMER, FALL
}

public class SeasonMessage {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String input = sc.nextLine().toUpperCase();
        Season season = Season.valueOf(input);

        switch (season) {
            case WINTER:
                System.out.println("It's cold outside. Stay warm!");
                break;
            case SPRING:
                System.out.println("Flowers are blooming. Enjoy the fresh air!");
                break;
            case SUMMER:
                System.out.println("It's sunny and hot. Time for the beach!");
                break;
            case FALL:
                System.out.println("Leaves are falling. Autumn is beautiful!");
                break;
        }
        sc.close();
    }
}

```

## OUTPUT:

<img width="947" height="243" alt="image" src="https://github.com/user-attachments/assets/766b2bf2-c830-464b-b5fb-6bd9e4c91e85" />


## RESULT:
The program to display a custom seasonal message using enum and switch statement was successfully executed and verified.
