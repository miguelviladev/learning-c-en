# Compilation cycle in C

As you probably know, a computer only understands 1's and 0's, but when writing C code you use symbols, characters, numbers. Take a look at this code example:

```c
#include <stdio.h>

int main(){
    printf("Hello C Language");
    return 0;
}
```

You can tell that this algorithm is written with English words, but our computer is incapable of understanding them. To execute the algorithm we need to convert this source code into binary code. That process is called **compilation**.

![](../0-resources/compilation-simple.png)

The compilation process can be divided into four sub-processes: pre-processing, compiling, assembling, and linking.

### 1. Pre-processing

The source code is written in a text editor such as Visual Studio Code and is given the extension ".c". After that, the code is passed to the pre-processor, a text substitution tool that instructs the compiler to do the required pre-processing before compiling.
<br><br>

> All pre-processor commands begin with a hash symbol (_#_).
>
> In the example above, the `include` directive tells the pre-processor to include the `stdio.h` library from System Libraries into the current source code file.

### 2. Compiling

### 3. Assembling

### 4. Linking

<br><br>
[[⬅️ BACK]](3-how-to-structure-a-program.md)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[[📋 TABLE OF CONTENTS]](../README.md)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[[NEXT ➡️]](../2-environment-setup-for-c/1-installation-on-linux.md)
