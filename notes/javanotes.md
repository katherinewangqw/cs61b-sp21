# CS61B

## Lec 1.1

The most common way to execute a Java program is to run it through a sequence of two programs. The first is the Java compiler, or `javac`. The second is the Java interpreter, or `java`.

When we give out our code, we give .class file. The reason for having a *class file* is because:

1. It is type checked. Distributed code is safer.
2. It is 'simpler' for machine to execute. Distributed code is faster. **Think this as if the file is already pre-chewed. It is easier to write an interpreter that reads a pre-chewed file**.



```c
#include <stdio.h>

int main(void) {
    printf("Hello World!\n");
    return 0;
}
```

![Test Image](pics/王冠.png)