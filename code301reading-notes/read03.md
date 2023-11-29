# Reading Class 03 

## Why is this important?

- .map() is important because it simplifies looping over an array that is given and storing that info into a new array.

- Waiting on class to describe the spread operator

- Passing functions between components is important so devs do not have to repeat code!

## React Docs - lists and keys

1. `.map()` returns a new array that contains the results of the provided function on every element in the calling array. [source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

2. you can use `.map()` or `.forEach()`

3. Each list item needs a unique key

4. "React uses your keys to know what happened if you later insert, delete, or reorder the items" [source](https://react.dev/learn#rendering-lists)

## The Spread Operator

1. The spread operator allows strings and arrays in places where zero arguments are expected. [source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)

2. 4 things a spread operator can do are : make a shallow copy of an array(a copy whose props share the same refs. as those of the source obj. [source](https://developer.mozilla.org/en-US/docs/Glossary/Shallow_copy)), replaces the apply() function, to merge multiple objects into a single one, as well as overriding object properties.

3. `const isDaytime = false;
    const activity = ['sleep', 'study', ...(isDaytime ? ["party"] : [])]`;

4. `const obj1 = { foo: "bar", x: 42 };
const obj2 = { bar: "baz", y: 13 };

const mergedObj = { ...obj1, ...obj2 };` [source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)

## How to Pass functions Between Components

1. The first step is: Defining two components? or attaching handleClick to the onClick attached to the button. 

2. The `handleClick` function is what needs to execute once the button is clicked by the user.

3. You can pass the method as a prop to the child `return <Child handleClick={handleClick} />`

4. Calling back to it as an argument in the child function

## Things I want to know more about?

- What is the actual first step for Passing functions between components according to the video.
