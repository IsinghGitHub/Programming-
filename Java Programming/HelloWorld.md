# Parameters used in First Java Program

Let's see what is the meaning of class, public, static, void, main, String[], System.out.println().

- **class** keyword is used to declare a class in java.
- **public** keyword is an access modifier which represents visibility. It means it is visible to all.
- **static** is a keyword. If we declare any method as static, it is known as the static method. The core advantage of the static method is that there is no need to create an object to invoke the static method. The main method is executed by the JVM, so it doesn't require to create an object to invoke the main method. So it saves memory.
- **void** is the return type of the method. It means it doesn't return any value.
- **main** represents the starting point of the program.
- **String[] args** is used for command line argument. We will learn it later.
- **System.out.println()** is used to print statement. Here, System is a class, out is the object of PrintStream class, println() is the method of PrintStream class. We will learn about the internal working of System.out.println statement later.

**By changing the sequence of the modifiers, method prototype is not changed in Java.**

Let's see the simple code of the main method.

```java
static public void main(String args[])
```

**The subscript notation in Java array can be used after type, before the variable or after the variable.**

Let's see the different codes to write the main method.

```java
public static void main(String[] args)  
public static void main(String []args)  
public static void main(String args[])

```

**You can provide var-args support to the main method by passing 3 ellipses (dots)**

Let's see the simple code of using var-args in the main method. We will learn about var-args later in Java New Features chapter.

```java
public static void main(String... args)
```

```java
public class Hello {

    public static void main(String[] args) {
        System.out.println("Hello World!");
        System.out.println("This is my test program on java");
    }

}

```

**Having a semicolon at the end of class is optional in Java.**

Let's see the simple code.

```java
class A{  
static public void main(String... args){  
System.out.println("hello java4");  
}  
};
```

**Valid java main method signature**

```java
public static void main(String[] args)  
public static void main(String []args)  
public static void main(String args[])  
public static void main(String... args)  
static public void main(String[] args)  
public static final void main(String[] args)  
final public static void main(String[] args)  
final strictfp public static void main(String[] args)
```

Invalid java main method signature

```java
public void main(String[] args)  
static void main(String[] args)  
public void static main(String[] args)  
abstract public static void main(String[] args)
```
