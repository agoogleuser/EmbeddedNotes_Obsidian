This Part of the linker Simply checks the Symbol table of each object file generated during the compilation of each intermediate file.

This tool checks the following
1. Every Needed object in a table is provided in another table
		Failing to do so will create the following error:
		`Error: Undefined refrence to <Object_Name>`
1. Every Provided Object exists in ***only one symbol table.***, unless you can hide them - which will be mentioned later -.
		Failing will create the following error:
		`Error: Multiple Definitions of <Object_Name>`

The next step is [[Output Generation]]

Tags: #Linker 
