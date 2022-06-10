# Inheritance

## Aim:

To write a C# program to print some messages using hierarchical inheritance.


## Algorithm:

Step 1: Create a base class.

Step 2: Create two child class.

Step 3: Create a constructor in the base class and print a message.

Step 4: create a function in child class to print a message.

## Program:

```python 3

using System;
namespace Hello
{
    public class vehicle
    {
        public vehicle()
        {
            Console.Write("Tyre is attached");
        }

    }
    public class car : vehicle
    {
        public void display()
        {
            Console.Write(" to car\n");
        }
    }
    public class scooter : vehicle
    {
        public void display()
        {
            Console.Write(" to scooter\n");
        }
    }
    public class program
    {
        public static void Main(string[] args)
        {
            car car = new car();
            car.display();
            scooter scooter = new scooter();
            scooter.display();
        }
    }
}

```

## Output:

![image](https://user-images.githubusercontent.com/81132849/172982245-d77894ce-c2fd-4c39-8cd6-d1dc0edbe917.png)



## Result

Thus, a C# program to print some messages using hierarchical inheritance was developed successfully.


