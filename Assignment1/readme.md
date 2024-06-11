
# Value types and reference types in Java
![alt text](https://github.com/Zaniiiii/Fpt-Assignment1/blob/main/Assignment1/images/valueVSreferences.png?raw=true)

In Java, there are two main types of data: value types and reference types. Here is an explanation of each:

## Value types
Java does not have built-in support for value types like some other programming languages (e.g., C# with its struct type). In Java, all primitive data types are value types. Value types store the actual data value directly in the variable, and they are passed by value. When you assign a value to another variable, a copy of the value is made.

### Examples

- int
- float
- double
- char
- boolean
- byte
- short
- long

### Characteristics

- **Memory Allocation**: Stored on the stack.
- **Copying**: When a value type is assigned to another variable, the value is copied. Both variables hold the same value, but they are independent of each other.
- **Performance**: Faster because they are stored on the stack and do not require complex memory management.

### Code Examples
```
public class Main {
    public static void main(String[] args){
        int myNum = 5;               // Integer (whole number)
        System.out.println("int: " + myNum);
        float myFloatNum = 5.99f;    // Floating point number
        System.out.println("float: " + myFloatNum);
        char myLetter = 'h';         // Character
        System.out.println("char: " + myLetter);
        boolean myBool = true;       // Boolean
        System.out.println("bool: " + myBool);
        String myText = "Hello World!";     // String
        System.out.println("string: " + myText);
    }
}
```

Output:
```
int: 5
float: 5.99
char: h
bool: true
string: Hello World!
```
