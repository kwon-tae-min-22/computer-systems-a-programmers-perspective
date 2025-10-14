```c
#include <stdio.h>
int main() {
    printf("Hello, World!\n");
    return 0;
}
```

```text
#  i   n   c  l   u   d   e   SP <  s   t   d   i   o   .  h   >  LF
35 105 110 99 108 117 100 101 32 60 115 116 100 105 111 46 104 62 10
i   n   t   SP m   a  i   n   (  )   SP  {  LF
105 110 116 32 109 97 105 110 40 41  32  123 10
... more lines ...

```

## 1.1 Information Is Bits + Context

Our hello program begins life as a source program (or source file) that the programmer creates 
with an editor and saves in a text file called hello.c. The source program is a sequence of bits, 
each with a value of 0 or 1, organized in 8-bit chunks called bytes.

The hello.c program is stored in a file as a sequence of bytes. Each byte has an integer value that 
corresponds to some character.

