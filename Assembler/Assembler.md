Assembler is the next step after compilation, It simply converts the target assembly code into its equivalent machine code. the output of this step is called an object file `file.o`, `file.exe` or `file.obj`

**NOTE** : In a project of multiple source files and libraries, The steps from pre-processing until the assembler are done for each source file ***independently***, the linker starts at the end to links all the object files 

After Doing this for all the source files in the project, the object files are forwarded to the [[Linker]] to combine them all into a single file that can be executed.
Tags : #Assembler