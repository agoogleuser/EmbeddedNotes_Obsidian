After Tokenizing the code, The compiler makes an Abstract or Asymmetrical Syntax Tree (AST), a tree data structure that helps the compiler understand the sequence of execution depending on the built-in compiler [[Operators]] Priority or Precedence.

This is also the part that is responsible for checking the correctness of the code, therefore it outputs a `syntax error` when it finds a problem with your code, those errors can be
- Missing semicolon \';\'
- Undefined keyword
	- `innt x = 5;`
- Wrong  type.
```c
char     x[] = "Hello, World";
int16_t  y   = x ; // <<===== Compilation Error
```

.
The Next step is the [[Temporary Generator]].
.
More Detail in Video: [Abstract Syntax Trees - 3m50s](https://www.youtube.com/watch?v=jpfaXK4xCYE)

.

Tags : #Compiler-Frontend, #Compiler