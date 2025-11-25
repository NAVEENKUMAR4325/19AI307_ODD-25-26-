# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Create a class Car with attributes brand, model, year. Create 2 objects and print their details.

## AIM:
To create a Car class with attributes brand, model, and year, and display details of two objects of the class.

## ALGORITHM :
1.Define a class named Car.
2.Declare three attributes: brand, model, and year.
3.Create a constructor to initialize these attributes.
4.Create a method to display the car details.
5.In the main method, create two objects of the Car class.
6.Print the details of both objects.





## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: Naveen Kumar E
RegisterNumber: 212222220029
*/
```

## SOURCE CODE:
```
public class CarDetails {

    static class Car {
        String brand;
        String model;
        int year;

        public Car(String brand, String model, int year) {
            this.brand = brand;
            this.model = model;
            this.year = year;
        }

        public String getDetails() {
            return this.brand + " " + this.model + " " + this.year;
        }
    }

    public static void main(String[] args) {
        Car car1 = new Car("Toyota", "Innova", 2022);
        Car car2 = new Car("Hyundai", "i20", 2021);

        System.out.println("Car 1: " + car1.getDetails());
        System.out.println("Car 2: " + car2.getDetails());
    }
}
```






## OUTPUT:

<img width="575" height="168" alt="image" src="https://github.com/user-attachments/assets/03a8666e-48bc-46e6-8014-a846a799b028" />


## RESULT:
The Car class was successfully implemented with attributes brand, model, and year. Two objects were created and their details were displayed correctly, confirming proper class functionality.



