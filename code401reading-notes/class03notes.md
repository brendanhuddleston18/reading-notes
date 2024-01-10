# Class 03 Notes: FileIO & Exceptions

## Why is this important?

- With statements contribute to cleaner code, efficient error management and devs don't have to manually close files

- `.read()` and `.readlines()` allows Devs to bring in external files and use possible data in their programs based on their size

- Exception handling is important for managing and isolating the source of errors as well as identifying which code needs to run despite errors.

## Reading Questions

- The `with` statement closes a file automatically once it leaves the `with` block [source](https://realpython.com/read-write-files-python/).  Makes code cleaner and easier to manage errors.  When it comes to external resources it utilizes context managers that help the setup and teardown phases.

- `.read()` Will read a file based on the bytes(`size=`) or the entire file if not given a parameter while `.readlines()` will read a number of characters (`size=`) given or the entire line if not given a parameter.  You can extract an entire file from an external source and utilize data from it in your program with `.read()`.  With `.readlines()` you can extract a certain line from a document and bring it in to your file as a string

- Exception handling in python is the process of creating and processing errors that might occur if a certain condition isn't met.  The `try` will attempt a code block that might have erros, if it fails the process will move to the `except` block which throws an error or whatever you want it to do based on if an error occurs.  Finally, the `finally` block (optional) is a block of code that will execute if an error occured or not.  `Try`: Get api from external source `Except`: API key is invalid. `Finally`: Store information from front end in database 

## Things I want to know more about

- What are real world examples of `Finally`