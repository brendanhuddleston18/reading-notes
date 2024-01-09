# Reading Class 02 Testing and Modules

## Why is this important?

- Test Driven Development is important to ensure efficiency, cleanliness, and effectiveness of code.

- Recursion simplifies code by allowing a function to produce multiple outputs with a dynamic set of inputs.

- Packages and modules contribute to modular programming by organizing and grouping sets of code that devs can import, export for other projects.

## Reading Questions

1. The key principles of TDD in Python are write a unit test that fails, write the feature and refactor the code.  These principles help with constant improvement and insurance that your code will perform as expected.  They also encourage simplistic and modular code.

2. "The `if __name__ == '__main__'` statement is used for testing whether your script is being run directly or being imported by something else." [source](https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/).  Some use cases are if you have code that you only want to run if the program is the main module and testing when scripts are run directly.

3. Recursion in Python is when a function calls itself inside of its body. Important to add a base case so the function knows when to stop, preventing an infinite loop.  "Direct recursive is if it calls the same function, indirect is if it calls another function" [source](https://www.geeksforgeeks.org/introduction-to-recursion-data-structure-and-algorithm-tutorials/)

4. A module is a python file created with the extension `.py`, it can be written in Python, written in C and loaded dynamically or be built-in. To import a module you simply adding `import moduleName` into your Python code.  You can use them by adding dot notation to the module name to access its functionality.  A package is a group of modules put into one directory to keep them organized.  You create packages by placing the desired(related) modules into a directory.  You can access the modules within a directory with dot notation when importing: `import pkg.mod1`

## Things I want to know more about

- Why does it matter if your script is being run directly?