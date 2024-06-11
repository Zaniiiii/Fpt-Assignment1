# OOP

Object-Oriented Programming (OOP) principles are fundamental concepts that guide the design and development of software using objects and classes. Java, being an object-oriented language, strongly supports these principles. The four main OOP principles are encapsulation, inheritance, polymorphism, and abstraction. Here is how these principles are implemented and utilized in Java:

## Encapsulation

Encapsulation is when data and the methods that work with the data are bundled together into a single unit called a class. It restricts access to some of the object’s components and prevents the accidental modification of data.

### Implementation

In Java, you can use access modifiers (private, protected, public) to control the visibility of variables and methods. For example:
```
public class Person {
    private String name;
    private int age;

    // Getter method for name
    public String getName() {
        return name;
    }

    // Setter method for name
    public void setName(String name) {
        this.name = name;
    }

    // Getter method for age
    public int getAge() {
        return age;
    }

    // Setter method for age
    public void setAge(int age) {
        this.age = age;
    }
}
```
