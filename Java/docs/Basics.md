# Basics

## Features
* **Simple** - No need to manage memory; no operator overloading.
* **Portable** - Java is platform independent.
* **Object-oriented** - Everything is considered to be an "**object**" which possess some state, behavior and all the operations are performed using those objects.
* **Secure**
  - JVM
  - Security API's
  - Security manager
  - Void of pointers
  - Memory management
  - Compile-time checking
  - Cryptographic security
  - Java sandbox
  - Exception handling
  - Java class loader
* **Dynamic** - It has the ability to adapt to an evolving environment which supports dynamic memory allocation due to which memory wastage is reduced and performance of the application is increased.
* **Distributed** - Java provides a feature which helps to create distributed applications. Using Remote Method Invocation (RMI), a program can invoke a method of another program across a network and get the output. You can access files by calling the methods from any machine on the internet.
* **Robust** - It checks the code errors during compile and runtime.
* **High Performance** - By using JIT (Just-In-Time) compilers, Java enables high performance.
* **Interpreted** - Java code is first compiled to bytecode, then interpreted by a Java runtime environment.
* **Multithreaded**

## Components
* **JVM (Java Virtual Machine)** - It is used to execute bytecode. The .java files are compiled to .class files by javac (JDK). Then .class files are interpreted to bit code by JVM.
  - **Specification:** It is a document that describes the implementation of the Java virtual machine.
  - **Implementation:** It is a program that meets the requirements of JVM specification.
  - **Runtime Instance:** An instance of JVM is created whenever you write a Java command on the command prompt and run the class.
* **JRE (Java Runtime Environment)** - JRE is a software package that contains what is required to run a Java program. It is an implementation of the JVM which physically exists.
* **JDK (Java Development Kit)** - Along with JRE, it includes an interpretor/loader, a compiler (javac), an archiver (jar), a documentation generator (javadoc) and other tools needed in Java development.
