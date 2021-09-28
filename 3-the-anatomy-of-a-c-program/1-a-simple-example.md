# A simple example

### 1. The main() function

Computer software consists of a group of ordered instructions and functions executed to solve a particular problem. When it comes to the C language, there is a function called **main()**, and all programs must have it.

```c
1:  main(){
2:
3:  }
```

It is the first function executed by default. Other instructions that we want to be executed must be written inside **{}** creating, what we call, a code block.

Please note, because **main** is a function, we must open and close parenthesis. All functions in C are written this way.

Also, remember that C is a case-sensitive language. This means that writing "**Main()**" instead of "**main()**" would result in a compilation error.

### 2. Adding functionality

If we were to execute this code, we would get absolutely nothing. That's because we only created a main() function. We didn't write any instructions for the computer to follow.

Lets add functionality to our program:

```c
1:  #include <stdio.h>
2:
3:  main(){
4:      printf("Hello world");
5:  }
```

As you can probably guess, now the computer will print "Hello world" on the console when executed.
