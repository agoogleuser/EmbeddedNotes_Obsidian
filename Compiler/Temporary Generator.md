Assuming No Syntax or Compilation errors exists in the the code, the compiler proceeds to convert the source code into a *pesudo-machine code*. This code is now made using LLVM Code, which is now a standard amongst compilers, after this, the next step is [[Target Generator]].
## Why this step exists ? why not immediately convert to the target assembly code ?
**Answer:** For convenience when porting the compiler to a new CPU Architecture, you don't want to mess with the logic of the programming language, you only need to make sure that the code is correctly translates to the target's assembly code. When Porting, you don't change anything in the front end of the compiler, only the back end of it.

Tags : #Compiler-Frontend, #Compiler