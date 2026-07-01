## Fundamentals
Pieces of these materials can be combined for workshops of various lengths and various levels of difficulty. Additional materials can be supplemented from the Next Steps materials. Previously taught versions of Fundamentals include a 4-day workshop (24 hours total) for beginners, a 3-day version (18 hours) for beginners, and a 4-day (24 hours) accelerated workshop for participants who are already strong coders in another coding language like R or SQL. Both remote and in-person workshops have been taught. Ungraded review quizzes for each part can be used as either in-workshop or optional homework exercises.

### Part 1: Objects and Functions [Colab link](https://colab.research.google.com/github/nuitrcs/python_fundamentals_aug2026_chicago/blob/main/part1.ipynb)
Part one introduces the concepts of object classes and functions. 
- Integers, floats, strings, and boolean objects
- Arithmetic operators: `+`, `-`, `*`, `/`, `**`, `//`
- Comparison operators: `>`, `>=`, `<`, `<=`, `==`, `!=`
- Logical operators: `and`, `or`, `not`
- Assigning objects to variables
- Special characters in strings
- Two types of functions: stand-alone and method functions
- Passing arguments to functions, default values, keyword arguments
- Changing string objects with functions and reassigning variables
- Stand-alone functions: `print()`, `len()`, `round()`, `type()`, `abs()`
- Changing object types with functions: `str()`, `int()`, `float()`
- String method functions: capitalization methods, removing and replacing characters methods, and more
- String indexing and returning substrings
- Coding story problems
- Interpreting basic Python errors
- Importing modules and using functions and objects from imported modules
- About built-in vs. installed libraries and where to find them (installing packages from inside a notebook is covered in Part 3.)

### Part 2: Collections and Loops [Colab link](https://colab.research.google.com/github/nuitrcs/python_fundamentals_aug2026_chicago/blob/main/part2.ipynb)
In part two, our Python code becomes more powerful. We introduce containers/collections - objects that hold other objects. We learn how to loop through those collections and filter objects based on conditions.
- Lists
- Mutable vs. immutable objects
- Stand alone functions that work with collection objects: `len()`, `sum()`, `min()`, `max()`
- List method functions: `sort()`, `append()`, `copy()`
- Functions from the `statistics` package
- List indexing
- Nested lists
- Joining items in a list into one string with `join()`
- Splitting a string into a list with `split()`
- for loops
- if statements (conditionals)
- Breaking a loop
- Nested loops
- The `in` boolean operator
- Basic error handling with try/except
- Adding items to an empty list
- Tuple objects
- Set objects for removing duplicate objects
- Looping through a range of numbers with the range object
- Dictionary objects
- Dictionary indexing
- Looping through dictionaries
- Filtering dictionaries and adding items to an empty dictionary
- Lists of dictionaries and dictionaries of dictionaries
- Hard coding and how to avoid it

### Part 3: Files [Colab link](https://colab.research.google.com/github/nuitrcs/python_fundamentals_aug2026_chicago/blob/main/part3.ipynb)
Part three covers reading and writing files in Python.
- Importing and installing modules (bonus review)
- Opening files with the `with`/`as` statement
- Reading files as a string or as a list of lines
- Writing files
- Cleaning files while reading (stripping whitespace, splitting lines)
- Turning a file into a dictionary
- Reading files line by line

### Part 4: Defining Your Own Functions [Colab link](https://colab.research.google.com/github/nuitrcs/python_fundamentals_aug2026_chicago/blob/main/part4.ipynb)
Part four teaches participants how to write their own reusable functions.
- Writing functions with no arguments
- Writing functions with one or more arguments
- Writing functions that return objects
- Default argument values
- Practice exercises applying functions to realistic problems

### Part 5: Final Exercise
Part five is a capstone project that brings together concepts from Parts 1–4. See [`part5-instructions.md`](part5-instructions.md) for the full prompt. Participants write a conversion calculator that:
- Reads unit conversion data from a CSV file
- Accepts user input for a value and unit
- Converts the value using data from the file and prints the result
