# Class 02 Reading Notes

## Continue Reading Intro. to HTML

1. It is important to use semantics in our HTML in order to give elements purpose. Semantic elements serve a role in the HTML document and also help paint the picture of what certain elements' tasks are for other developers who might be looking at your code.

2. There are six levels of headings in html. They are written like this: `<h1>` `<h2>` `<h3>` `<h4>` `<h5>` `<h6>` they also very in size(you can change the size in CSS) but H1's are the largest and H6's are the smallest.

3. "Uses of `<sup>` and `<sub>` could be math equations, chemical formulae, and dates" - [source](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

4. The `title=""` attribute must be added to provide the full expansion of the term. Ex: `I think <abbr title="HyperText Markup Language">HTML</abbr> is super cool`

## Learn CSS

1. You can apply CSS internally, externally and inline.
   Internally: Using the `<style>` tag in the `<head>` of the element.
   Externally: Making a stylesheet, usually named `style.css`, and linking it to the html document: `<link rel="stylesheet" href="style.css">`.
   Inline: Which is not best practice but you can add a style attribute directly to an HTML tag: `<p style="color: blue">`.

2. We should avoid using inline styles because it is very inefficient and also very hard to read since it is mixed into the HTML as well.

`h2 {
     color: black;
     padding: 5px;
   }`

3.  (1)The h2 element is representing the selector in this example. (2) The `color: black;` and `padding: 5px;` are CSS declarations. (3) The `color:` and `padding:` are the actual properties

## Learn JS

1. The string datatype is a sequence of text enclosed in single quote marks. Ex: `'I am a string'`

2. 4 types of JavaScript Operators are: Addition `+`, Assignment `=`, Not `!`, and strict/loose equality `===`/`==`

3. A real world problem I could solve with a function is: Is prompting a student to enter their name into a prompt function in order to take attendance for class.

## Learn JS pt. 2

1. An if statement checks a condition and if it evaluates to true, then the code block will execute.

2. `else if` is used to add another condition to your if statment.

3. 3 different type of comparison operators are: Greater/less than `>`/`<`, strict equality `===`(left and right values must be exactly identical), Less/Greater than or equal to `<=`/`>=`

4. The `&&` logical operator means 'and', so both values on either side of the operator must result to true in order for the statement to be true. The `||` logical operator means 'or' so only one value on either side of the operator needs to be true in order for the result to be true.

## Things I want to know more about

- Is there to different functions? `alert()` vs `function()`? Confused on this
