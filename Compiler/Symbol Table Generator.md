This is a very important part for the compiler, used by the [[Linker]].
It creates a table containing each and every variable used in the source file, and gives it a virtual address.
for example, a table should be something like this:

| Object Name | Type | Virtual Address | Authority or Ownership |
| :---- | :---- | ----: | ---: |
| *x* | int | 0x00 | Provided|
| func | void(void)| 0x04 | Needed|
| y | float | 0x08 |Provided|

Authority/Ownership says if the object is provided in the source file or in another source file, this is acknowledged by the compiler when using the keyword [[extern]] , where the object is declared at the source code file, but its definition is in another source code file.

This Table is saved into a temporary file, either a separate file, or at the beginning of the assembly code as a comment, as it's needed to be used by the [[Linker]]


Tags : #Compiler #Compiler-Backend