# Java SpringBoot Sample AOP Logger

This is a basic logger using Spring's Aspect Oriented Programming(AOP).

# Aspect Oriented Programming(AOP)

The AOP can be divided into core and cross-cutting concerns.

And the logic is simpler and more maintainable.

![AOP_Image](https://user-images.githubusercontent.com/36861752/86082839-b1148800-bad3-11ea-9d9c-1c88b42bb1af.png)

# Test Target Annotation
@Before, @After, @Around, @AfterReturning, @AfterThrowing

# Hello1 Case Procedure

1, Project Execution.

2, Access to "http://localhost:8080/hello1".

3, A log is output to the console.

4, The output of "Hello World 1" to the browser.

![hello1](https://user-images.githubusercontent.com/36861752/86082854-be317700-bad3-11ea-9934-c6cf85a2f235.jpg)

# Hello2 Case Procedure

1, Project Execution.

2, Access to "http://localhost:8080/hello2".

3, A log is output to the console.

4, There's no output to the browser.

![hello2](https://user-images.githubusercontent.com/36861752/86082879-cab5cf80-bad3-11ea-9bf5-053f5e3915b9.jpg)

# Hello3 Case Procedure

1, Project Execution.

2, Access to "http://localhost:8080/hello3".

3, A log is output to the console.

4, The console and browser output an error.

![hello3](https://user-images.githubusercontent.com/36861752/86082904-d5706480-bad3-11ea-9c9f-e48bdde7dd15.jpg)

