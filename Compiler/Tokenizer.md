The first part of the compilation process is reading the source code, specifically the intermediate code `file.i` 

In this section of the compiler, the compiler reads every word, and use it as a token, for example, the following line of code:
```c
int varZ = varX +        varY;
```
Note that I Have deliberately left a large number of spaces.

The Tokenizer will read the above line, it will collect each word and ***ignore spaces*** until it reaches the semicolon \`;\` and when finishes, those tokens are passed to the next step, that is the [[Syntax Tree]]

Tags : #Compiler-Frontend, #Compiler

