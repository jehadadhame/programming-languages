# Implementation Methods
![[Layered View of Computer.png]]
## Compilation 

- Translate high-level program (source language) into machine code (machine language)
- Slow translation, fast execution
- Compilation process has several phases:
	- lexical analysis: converts characters in the source program into lexical units
	- syntax analysis: transforms lexical units into parse trees which represent the syntactic structure of program
	- Semantics analysis: generate intermediate code
	- code generation: machine code is generated
![[The compilation process.png|500]]

## Additional Compilation Terminologies
- Load module (**executable image**): the user and system code together
- **Linking** and loading: the process of collecting system program units and linking them to a user program
## Von Neumann Bottleneck
- Connection speed between a computer’s memory and its processor **determines the speed** of a computer
- Program instructions often can be executed much faster than the speed of the connection; the **connection** speed thus results in a **bottleneck**
- Known as the **von Neumann bottleneck**; it is the primary limiting factor in the speed of computers

## Pure Interpretation

- No translation
- Easier implementation of programs (run-time errors can easily and immediately be displayed)
- Slower execution (10 to 100 times slower than compiled programs)
- Often requires more space
- Now rare for traditional high-level languages
- Significant comeback with some Web scripting languages (e.g., JavaScript, PHP)
![[Pure Interpretation Process.png]]

## Hybrid Implementation Systems

- A compromise between compilers and pure interpreters
- A high-level language program is translated to an intermediate language that allows easy interpretation
- Faster than pure interpretation
- Examples
	- Perl programs are partially compiled to detect errors before interpretation

	- Initial implementations of Java were hybrid; the intermediate form, byte code, provides portability to any machine that has a byte code interpreter and a run-time system (together, these are called Java Virtual Machine)
![[Hybrid implementation system.png]]

## Just-in-Time Implementation Systems

- Initially translate programs to an intermediate language 
- Then compile the intermediate language of the subprograms into machine code when they are called
- **Machine code** version is **kept** for **subsequent calls**
- **JIT** systems are widely used for **Java** programs
- .**NET** languages are implemented with a **JIT** system
- In essence, **JIT** systems are **delayed compilers**