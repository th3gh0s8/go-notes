-
- # Go Language Notes - Basic Concepts
- ## Introduction
  Basic Go program demonstrating fundamental programming concepts including variables, constants, printing functions, and type inspection.
- ## Program Structure
- ### Package Declaration
  ```go
  package main
  ```
  Every Go program begins with a package declaration. The `main` package is special as it contains the entry point for executable programs.
- ### Import Statement
  ```go
  import "fmt"
  ```
  Imports the `fmt` package which provides formatted I/O functions like `Println` and `Printf`.
- ## Variable and Constant Declarations
- ### Explicit Variable Declaration
  ```go
  var name string
  name = "gh0s8"
  ```
- Uses the `var` keyword for explicit declaration
- Two-step process: declare first, then assign
- Declares a string variable named `name`
- ### Constant Declaration
  ```go
  const age = 25
  ```
- Declared using the `const` keyword
- Immutable values that cannot be changed once defined
- Type is automatically inferred by Go
- ### Short Variable Declaration
  ```go
  year := 2025
  ```
- Uses Go's short declaration syntax (`:=`)
- Combines declaration and initialization in one step
- Type is inferred from the assigned value
- ## Comments in Go
- ### Multi-line Comments
  ```go
  /* fmt.Printf("Hi %s \n", name)
  age += 1 */
  ```
  Block-commented code that would print a greeting and increment the age.
- Uses `/* */` syntax for multi-line comments
- Comments in Go use `//` for single-line and `/* */` for multi-line
- ### Single-line Comments
  ```go
  // This is a single-line comment
  // var anotherVariable = 10
  ```
- Begin with `//` and continue to the end of the line
- Useful for brief explanations or temporarily disabling code
- ## Output Functions
- ### Println Function
  ```go
  fmt.Println("Hi", name)
  fmt.Println("How are you")
  fmt.Println("You are", age, "Years Old in Year", year)
  ```
- Outputs text with automatic spacing between arguments
- Adds a newline character at the end
- ### Printf Function
  ```go
  fmt.Printf("Name is %T, Age is %T\n", name, age)
  ```
- Provides more control than `Println`
- Uses format specifiers:
	- `%T` prints the type of the variable
	- `\n` adds a newline character
- Requires format strings
- ## Key Takeaways
- **Three ways to declare variables:** `var`, explicit assignment, and short declaration (`:=`)
- **Constants:** Using `const` for immutable values
- **Printing:** Both `Println` (simple) and `Printf` (formatted) options
- **Types:** Go's static typing system with automatic inference
- **Comments:** Using `/* */` for multi-line comments and `//` for single-line comments
  
  This example serves as a solid foundation for understanding basic Go syntax and conventions!