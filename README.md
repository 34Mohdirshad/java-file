
📘 Java Learning Document

# Introduction to Java

Java is a popular, object-oriented programming language.

Used for web apps, mobile apps (Android), desktop apps, cloud & enterprise systems.

Follows the principle “Write Once, Run Anywhere” (WORA).



---

# Why Learn Java?

Easy to learn, widely used, and stable.

Supports OOP (Object-Oriented Programming).

Strong community support.

High demand in software industry.



---

# Prerequisites

Basic programming knowledge (optional but helpful).

Install Java Development Kit (JDK) → Download JDK

Install an IDE (Eclipse, IntelliJ IDEA, or VS Code).



---

# Step 1: Hello World Program

class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}

👉 Compile and run:

javac HelloWorld.java
java HelloWorld


---

# Step 2: Java Basics

Variables – Store data.


int age = 25;
String name = "Irshad";

Data Types – int, double, char, boolean, String.

Operators – +, -, *, /, %, ++, --, ==, !=, &&, ||.



---

# Step 3: Control Statements

// if-else
if (age >= 18) {
    System.out.println("Adult");
} else {
    System.out.println("Minor");
}

// loop
for (int i = 1; i <= 5; i++) {
    System.out.println(i);
}


---

# Step 4: Functions (Methods)

public class Calculator {
    public static int add(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        System.out.println(add(10, 5));  // Output: 15
    }
}


---

# Step 5: Object-Oriented Programming (OOP)

Class & Object


class Car {
    String brand;
    int speed;

    Car(String b, int s) {
        brand = b;
        speed = s;
    }

    void display() {
        System.out.println(brand + " runs at " + speed + " km/h");
    }
}

public class Main {
    public static void main(String[] args) {
        Car c1 = new Car("BMW", 200);
        c1.display();
    }
}

OOP Concepts:

1. Encapsulation (data hiding with getters/setters).


2. Inheritance (child class inherits parent).


3. Polymorphism (method overloading/overriding).


4. Abstraction (abstract classes & interfaces).





---

# Step 6: Exception Handling

try {
    int result = 10 / 0;
} catch (Exception e) {
    System.out.println("Error: " + e.getMessage());
}


---

# Step 7: Collections Framework

import java.util.*;

public class Main {
    public static void main(String[] args) {
        ArrayList<String> list = new ArrayList<>();
        list.add("Java");
        list.add("Python");

        for (String lang : list) {
            System.out.println(lang);
        }
    }
}


---

# Step 8: Java Learning Roadmap

1. Week 1 → Java Basics (syntax, variables, data types, loops).


2. Week 2 → Functions & OOP (class, object, inheritance, polymorphism).


3. Week 3 → Exception handling & collections.


4. Week 4 → File handling, multithreading, JDBC.


5. Week 5+ → Build projects (Calculator, Student Management System, Banking App).




---

# Resources to Learn Java

Official docs: https://docs.oracle.com/javase/

Free tutorials: https://www.w3schools.com/java/

Practice: https://www.hackerrank.com/domains/tutorials/10-days-of-java


