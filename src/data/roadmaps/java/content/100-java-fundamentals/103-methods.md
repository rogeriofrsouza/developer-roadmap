# Methods

In the Java programming language, a method is a block of code declared inside a class to perform some actions. Methods (also known as functions in other programming languages) provide reusability of code (through the 'DRY' principle i.e., "Do not repeat yourself") and can operate on the internal state of objects.

### Usage

1. Method declaration
```java
public int compute(int x, int y) {
    // implementation goes here...
}
```
2. Method invocation - ```compute(1, 2)```
3. Lambda expression - ```x -> x + 1```
4. Method reference
```java
Consumer<Integer> reference = App::someMethod;  
reference.accept(1);
```

Visit the following resources to learn more:

- [@official@Defining Methods](https://dev.java/learn/classes-objects/defining-methods/)
- [@official@Writing Your First Lambda Expression](https://dev.java/learn/lambdas/first-lambdas/)
- [@article@Methods/Functions in Java.](https://www.javatpoint.com/method-in-java)
- [@article@Learn Functions/Methods in Java](https://www.w3schools.com/java/java_methods.asp)
- [@video@Functions / Methods in Java](https://www.youtube.com/watch?v=vvanI8NRlSI)
- [@article@Lambda functions](https://www.w3schools.com/java/java_lambda.asp)
- [@article@Passing functions as a variable](https://northcoder.com/post/passing-java-functions-in-variables/)
