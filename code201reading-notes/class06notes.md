# Class 06 Reading Notes

## Why this is important

- The objects in JavaScript because they provide a more specific way to access information and group related items together without using an array.

- The DOM kinda seems like the backbone of web documents.

## JavaScript Object Basics 

1. An object is like a having a seperate shelf for books of the same genre.  "An object is a collection of related data and/or functionality...consist of several variables and functions" [source](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

2. Some advantages of creating object literals are that it is more efficient and it is easier to work with than an array.  `Object Literal`: "Written out the object contents as we've come to create it" [source](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

3. Objects are compartmentalized based off of the keys and values.  They're easier to understand what the role of the object is.

4. An example of when you would need to use bracket notation to access an object's property is if an object property name is held in a variable.

5. `this` refers to the current object the code is being written inside and the advantage being that if you create more than one object, it enables you to use the same method defintion for every object you create.

## Introduction to the DOM

- Document Object Model (DOM) is an interface for web documents that represents the page in order for certain programs to adjust the document structure, style and content.  The entirety of a web document is apart of the DOM. 

- JavaScript relies on the DOM in order to understand webpages, HTML docs, svg documents and their component parts.  

## Things I want to know more about

- Definitely still fuzzy on question 4/5 of the JS section, specifically the "if an object property name is held in a variable" and the point of `this` if you could just use the object name.

- Does `this` stay in the local scope of the current object? So you could reuse the object?

- What is an API?

## In class lecture

- Cards and Decks, create the containers "deck" and you can have divs act as "cards".  Then you can keep copying them if need be.

- Objects, properties= "has" values, any valid datatype, methods="can" actions, verbs, what you can do 'function'. Define using `{}`. Access properties + methods with dot notation:  `object.property` `object.method`.

- Key/Value pairs: `name: 'Geno'` key then value.

- `this` refers to an instance.  In class ex. `geno` is an instance of an object. Only works within the instance.  It 'is' the instance.

- You should never directly change property values.

- DOM = Document Object Model.  