The Compiler part is one of the biggest part of the compiling toolchain, as it's responsible for converting the C code understandable by humans into assembly code  for the target device.
It consists from 6 parts, that are divided into two parts, the front end, and the back end, **Those parts are:**
# **front end:**
1- [[Tokenizer]]
2- [[Syntax Tree]]
3- [[Temporary Generator]]
# **back end:**
4- [[Target Generator]]
5- [[Optimizer]] (Optional)
6- [[Symbol Table Generator]]

The Final Output of this process is the assembly code  for the target.`file.asm`, which is forwarded to the next step : [[Assembler]]. Additionally, in the last stage, a temporary files are made for the Symbol Table Generator that is required by the linking process at the end of building the project.