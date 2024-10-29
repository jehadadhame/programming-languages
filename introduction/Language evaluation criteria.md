# Language evaluation criteria
## Readability:

### Overall simplicity
- A <span style="color:rgb(0, 176, 240)">manageable</span> set of features and constructs
- Minimal feature <span style="color:rgb(0, 176, 240)">multiplicity</span>
	- having more than one way to accomplish a particular operation, like these four statements have the same meaning when used as stand- alone expressions.
		- `count = count + 1` 
		- `count += 1`
		- `count++ `
		- `++count`
- Minimal operator <span style="color:rgb(0, 176, 240)">overloading</span>
	- like using + for <code>print string</code>
### Orthogonality
- A relatively small set of <span style="color:rgb(0, 176, 240)">primitive constructs</span> can be combined in a relatively small number of ways
	- **<span style="color:rgb(0, 176, 240)">Primitive Constructs</span>**: These are the fundamental elements or basic operations provided by the language (e.g., data types, control structures like loops or conditionals).
- Every possible combination is legal

### Data types
- Adequate predefined data types, Adequate:
	- Language provide a well-rounded set of <span style="color:rgb(0, 176, 240)">common</span> data types
	- don't provide too many predefined data type like on numeric give us `small int` `int` `big int` ..etc. `int` enough 
	
### Syntax considerations
- Identifier forms: flexible composition
	- allow developers to choose flexibly there variable name,  <span style="color:rgb(0, 176, 240)">meaningful</span> names for their <span style="color:rgb(0, 176, 240)">identifiers</span>
- Special words and methods of forming compound statements
	- like group statements in {} 
- Form and meaning: self-descriptive constructs, meaningful keywords
	- <span style="color:rgb(0, 176, 240)">**semantics**</span> (the meaning of a program) should be <span style="color:rgb(0, 176, 240)">clearly</span> and systematically <span style="color:rgb(0, 176, 240)">derived</span> from the <span style="color:rgb(0, 176, 240)">**syntax**</span> (the structure or form of the program).

## Writability

### Simplicity and orthogonality
- Few constructs, a small number of primitives, a small set of rules for combining them
### Support for abstraction
- The ability to define and use complex structures or operations in ways that allow details to be ignored
### Expressivity
- A set of relatively convenient ways of specifying operations
- Strength and number of operators and predefined functions

## Reliability

### Type checking
- Testing for type errors
### Exception handling
- Intercept run-time errors and take corrective measures
### Aliasing
- Presence of two or more distinct referencing methods for the same memory location
### Readability and writability
- A language that does not support “natural” ways of expressing an algorithm will require the use of “unnatural” approaches, and hence reduced reliability

## Cost
- **Training programmers** to use the language
- **Writing programs** (closeness to particularapplications)
- **Compiling programs**
- **Executing programs**
- Language implementation system: **availability of free compilers**
- **Reliability:** poor reliability leads to high costs
- **Maintaining** programs


## Others
### Portability
- The ease with which programs can be moved from one implementation to another
### Generality
 - The applicability to a wide range of applications
### Well-definedness
- The completeness and precision of the language’s official definition