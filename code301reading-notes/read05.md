# Class 05 Reading Notes

## Why is this important?

- State in react is important to render changes in your application based on certain data.  You can also pass that down to child components who may use it. 

- Higher-Order Functions are important if you need to callback to a function multiple times within a function

## Thinking in React

1. The `single responsibility principle` is a ruling saying a component in your react app should only have one job and if it ends up doing more you should break it down into smaller componenents.

2. Is builiding a version of your site without any interactivity or dynamic capabilities.

3. By implementing state into your application so you can make minimal dynamic changes to the UI

4. 3 Questions you can ask to dtermine if something is state are: "Does it remain unchanged over time? If so, it isn’t state. Is it passed in from a parent via props? If so, it isn’t state. Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!" [source](https://react.dev/learn/thinking-in-react)

5. By identifying which components render an element based on the state and placing it at the level that can communicate with all of them.

## Higher-Order Functions

1. "Functions that operate on other functions, by taking them as arguments or by returning them." [source](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

2. Line two is a function that will return true if `m` is greater than `n`.

3. Map operates by returning the same amount of values(given by an array) to a new array and can apply a function for each value given.

## Things I want to learn

- What is a use case of reduce?