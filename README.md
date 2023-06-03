# Ex-8-Write-a-java-program-using-inheritance...

## AIM:

To write a java program using inheritance.

## ALGORITHM:

### Step 1:

Import the necessary packages.

### Step 2:

Get the elements values in array from the user.

### Step 3:

Create a class 'Animal' and create a method 'walk' in that class.

### Step 4:

Create another class named 'Bird' which inherits class 'Animal' and contains a method 'fly'

### Step 5:

Add a method 'sing' in the bird class.

### Step 6:

Create an object and call all the methods of the class 'Bird'.

### Step 7:

Print the result.

### Step 8:

End the program.

## PROGRAM:

``` java

Name   : Anto Richard. S
Reg No : 212221240005

class Animal{
    void walk()
    {
        System.out.println("I am walking");
    }
}

class Bird extends Animal
{
    void fly()
    {
        System.out.println("I am flying");
    }
    void sing()
    {
        System.out.println("I am singing");
    }
}


public class Main{
    public static void main(String args[])
    {
        Bird bird = new Bird();
        bird.walk();
        bird.fly();
        bird.sing();
    }
}

```

## OUTPUT:

![g5](https://github.com/anto-richard/Ex-8-Write-a-java-program-using-inheritance.../assets/93427534/3a60a6e0-7130-45e6-8b9a-11408ddcaaa1)

## RESULT:

Thus the java program using inheritance is executted successfully.

