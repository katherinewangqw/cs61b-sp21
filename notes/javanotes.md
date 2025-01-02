# CS61B

This file takes notes when reading CS61B [course material](https://joshhug.gitbooks.io/hug61b/content/chap1/chap11.html) and the videos. 

## Lec 1.1

### About java
The most common way to execute a Java program is to run it through a sequence of two programs. The first is the Java compiler, or `javac`. The second is the Java interpreter, or `java`.

When we give out our code, we give .class file. The reason for having a *class file* is because:

1. It is type checked. Distributed code is safer.
2. It is 'simpler' for machine to execute. Distributed code is faster. **Think this as if the file is already pre-chewed. It is easier to write an interpreter that reads a pre-chewed file**.

One thing to note is that Java is static typed, and python is dynamic typed. Java checks the code before the program runs! While python does not. Therefore, there's no chance that somebody running a java program will ever run into a type error!

### Doc your code
One important thing is to comment your code (so-called [Javadoc](https://en.wikipedia.org/wiki/Javadoc) format), as well as writing code following the [style-guide](https://sp19.datastructur.es/materials/guides/style-guide.html).


```c
// import statements

/**
 * @author      Firstname Lastname <address @ example.com>
 * @version     1.6                 (current version number of program)
 * @since       1.2          (the version of the package this class was first added to)
 */
public class Test {
    // class body
}
```

![Test Image](pics/王冠.png)