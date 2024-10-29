
# Influences on Language Design

## Computer Architecture  Influence

- Well-known computer architecture: **Von Neumann**
- **Imperative** languages, most dominant, because of von Neumann computers
	- Data and programs stored in memory
	- Memory is separate from CPU
	- Instructions and data are piped from memory to CPU
	- Basis for imperative languages
		- Variables model memory cells
		- Assignment statements model piping
		- Iteration is efficient

## Von Neumann Architecture:

![[Von Neumann.png]]

- **Fetch-execute-cycle** (on a von Neumann architecture computer)

	`initialize the program counter`
	`repeat forever`
	`fetch the instruction pointed by the counter
		`increment the counter`
		`decode the instruction`
		`execute the instruction`
	`end repeat`

## Programming Methodologies Influences

- 1950s and early 1960s: Simple applications; worry about machine efficiency
- Late 1960s: People efficiency became important; readability, better control structures
	- structured programming
	- top-down design and step-wise refinement
- Late 1970s: Process-oriented to data-oriented
	- data abstraction
- Middle 1980s: Object-oriented programming
	- Data abstraction + inheritance + polymorphism
