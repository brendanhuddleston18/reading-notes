# Class 03 Reading Notes

## Why this matters

- Differentiating between the two types of lists is important based on precedence/heirarchy of list items

- The Box Model helps with spacing between elements and within elements inorder to make the website look how the User would appreciate it.

- JavaScript arrays are a great way to store multiple list like values in one variable.  Operators are important for assignment of variables and values.  Condtions are great for requiring a certain input from a user and loops could continue to prompt that input until the user gets it correct.

## Learn HTML

1. You should use an `unordered list` when you want to list content that doesn't require a specific heirarchy or numerical precedence

2. You change the `bullet style` of ul list items with the `list-style-type` property in in your CSS

3. You should use an `ordered list` when the list items in your list have varying importance or are sequential.

4. Two ways you can change the numbers on `list items` are using the `start` attribute. Ex: `Start=4`. The list will then start from 4 instead of one.  and `reversed` which will make the list count down as the list items continue.

## The Box Model

1. "The Box Model" by Brendan Huddleston.  One day there was a nice house in Texas. There was the interior of the house(not including furniture which would be the content), which we'll call padding, it was the space inside the house which magically could grow depending on if the owner want to make the house take up more space or not.  Then there was the yard, which we'll call the margin, that could also change size depending on the owner's decision.  But the yard would seperate the house from other houses in the neighborhood.  THE END

2. Four parts of the box are: The Content which is the are where content is displayed.  Padding which is the area between the content and the border of the element.  Border Box which surrounds the content and padding.  The margin which wraps the entirety of the previous parts and acts as a buffer between other elements. 

## Arrays. Operators and Expressions.  Condtionals.  Loops

1. "You can store: strings, numbers, objects, and other arrays" - [Source](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)

2. It is a valid array, in order to access the values stored you would need to use the variable and `[]` with which array you want to choose.  Then use another set of `[]` to access whatever item inside of interior array.  Ex: `people[1][3]` would come back with librarian.

3. Five shorthand operators for assignment in javascript are:

- The addition assigment `x += y`, which means that x is the value of x plus whatever value `y` is.

- The multiplaction assignment `x *= y`, x is the value of x times y

- The subtraction assignment `x -= y`, x is the value of x minus y

- The division assignment `x /= y`, x is the value of x divided by y

- Logical or assignment `x ||= y`, x is true or (x = y) is true.

4. The result would be `10dog` I got this answer from doing the code on my own in replit.  I originally thought it would be `10falsedog`, and looked to chatgpt in order to find out why it wasn't: "Since 'c' is a boolean value, false=0, so 10 + 0 = 10" -Chatgpt

5. A real world situation of a conditional statement would be a VIP party.  If(person is on the guest list){let them in} else {Tell them to leave};

6. A loop could be useful in javascript when you want to visualize an input from the user with correlating icons.  Like showing 1-5 stars on a class survey depending on what the student rated the class.  

`for (let x = 1; x <= stars; x++){document.write(star icon);}`

## Things I want to know more about

- Arrays.  Question 2 confused me.  So when you want to access the information in the array, do you use the number item it is in the array or do you use the actual value? Ex. `people[1][3]` vs `people[1]['librarian']`
