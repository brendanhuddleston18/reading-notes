# Class 07 Reading: OOP, HTML Tables

## Why is this important?

- Tables help with the portrayal of important data that the user might be interested in.

- Constructors allow for the easy creation of objects based off of prior objects

## Domain Modeling

1. We need domain modeling because it creates a common understanding of the scope of the problem it describes and various attributes and entities within the model.  Domain models can also act as documentation for the devs and system.

## HTML 

1. Tables should not be used for page layouts because they "reduce accessibility for visually impaired users", since tables involve more complex markup structures they have a lot of tags and can be "hard to write, maintain and debug", "Tables are not auto. responsive" meaning they only take up the size of their content and don't default to 100% of their parent element. - [source](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

2. 3 different semantic HTML elements used in a `<table>` are `<td>` which is a table cell and is the smallest container inside of the table, `<tr>` Which is used to place a new row so the previous row doesn't grow with each new td element and the last is `<th>` which provide the table with headers that are place at the start of a row or column.

## Introducing Constructors

1. A constructor is a function that creates a new object based on a previous object so they have the same keys.  Some advantages of constructors are that they are more efficient than creating a function that creates a new object and having to invoke the function and initialize the new object.  It also reinforces code reusability and specializes in consistency between objects. 

2. `this` in an object literal refers to the object that it is currently in while in a constructor it refers to the object being created by the constructor.

## Object Prototypes Using A Constructor

1. I'm going to explain this the best I can.  Prototypes in my previous work experience would be the standard army training that everyone gets once they enter and then inheritance would be the specialized Forward Observer training that I specifically received since it was my job.  

## Things I want to know more about

- For number 2 in the constructor section, feel like `this` means a very similar thing in both objects and constructors.

- Would like more light shed on prototypes and inheritance.  It can't be that easy to understand right?