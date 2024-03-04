# Class 42 Notes Pythonisms

## Why is this important?

- Pythonisms are important for understanding and implementing methods to making your code more efficient.

## Reading Questions

1. Dunder methods let you emulate the behavior of built-in methods.  You can create a class and give it dunder methods for functions that you want it have like `__len__` for length or `__str__` to return a string representation of what ever is passed in.

2. An iterator in Python is used to traverse over each element in an iterable object like lists, dictionaries and tuples.  You can create a custom iterator by implementing `__iter__()` and `__next__()` methods in your class.  `__iter__()` returns the iterable object while `__next__()` returns the following item.  Iterators are important because they allow for more control of the iteration and can be more memory efficient.

3. A generator is an iterator defined in a function which uses the `yield` keyword to produce sequential values.  Compared to regular functions, generator functions are more memory efficient, use yield vs return and is able to pick up where it last left off.

`def repeater(value):
    while True:
        yield value`

4. A decorator takes in a function and extends its behavior on the latter function without modifying it.  [source](https://realpython.com/primer-on-python-decorators/) You can create a simple decorator using `@decoratorname`.  A simple example would be `@functools.wrap(func)`

## Things I want to know more about

- N/A