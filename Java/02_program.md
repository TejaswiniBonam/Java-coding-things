# Execution Process of a Java Program

The execution of a Java program involves several key steps from writing the code to running the application. Here’s a step-by-step overview:

## 1. Writing the Source Code
- The programmer writes Java source code in a file with a `.java` extension.

## 2. Compilation
- The Java source file is compiled using the Java Compiler (`javac`).
- The compiler translates the source code into bytecode, generating a `.class` file.

## 3. Class Loading
- The Java Class Loader loads the compiled `.class` files into memory when the program is run.

## 4. Bytecode Verification
- The Bytecode Verifier checks the loaded bytecode for security and correctness.

## 5. Execution by JVM
- The Java Virtual Machine (JVM) interprets or just-in-time (JIT) compiles the bytecode into native machine code.
- The program starts execution from the `main` method.

## 6. Program Output
- The JVM executes the program, and the output is displayed to the user.

---

**Summary Diagram:**

```mermaid
graph TD
    A[Write Java Code] --> B[Compile with javac]
    B --> C[Bytecode (.class file)]
    C --> D[Class Loader]
    D --> E[Bytecode Verifier]
    E --> F[JVM Execution]
    F --> G[Program Output]
```


# how to take input
* Using `Scanner` class from `java.util` package 
* `Scanner sc = new Scanner(System.in);`
* `sc.nextInt(), sc.nextDouble(), nextFloat(), nextBoolean(), nextByte(), nextLong(), nextShort() for diff data types`
* `sc.next()` to take a TOKEN (until it trigegrs a white space)
* `sc.nextLine()` - to take a line string (till it gets \n.
