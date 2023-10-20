# Class 01 Reading Notes

## Getting Started

1. HTTP, HyperText Transfer Protocol utilizes ports in order to send packets or data between computers via the Internet or Ethernet

2. I like to think of HTML, CSS, and JavaScript as parts of the human body in regards to a website. What I mean by that is that HTML is the skeletal system, it provides the foundation to the website. CSS is the skin and other cosmetic features, it goes off the HTML and makes the website pretty and appealing to look at. JavaScript is the muscular system because it allows the website to be dynamic and have functionality tailored to the user.

3. You can use stock images or even Google's license filter. Some stock image websites are unsplash.com and squoosh.app

4. A string data type is created using the single quotes: `'String'` or `'5'` while numbers lack the single quote: `5`.

5. A variable in JavaScript is a box or container used to store values, for example. `let myName = 'Brendan';` The container or variable is `myName` and the content of the variable(container) is the string `'Brendan'`. They are important in JavaScript in order to create dynamic programming like prompting the user for their name and then personalizing an alert with the user input.

## Introduction to HTML

1. Attributes give an HTML element extra characteristics like assigning the element to a class: `class=""` or telling the element which file it will use as its stylesheet source: `src=""`

2. An HTML element consists of 3 things (not including attributes): An opening tag: `<h1>`, a closing tag: `</h1>` and the content inbetween the opening and closing tags: `This is a level one heading`

3. `<article>` Groups together similar content that the user can comprehend without the rest of the webpage while `<section>` groups together a singular part of the page that has one specific use.

4. A typical webpage includes: `<!DOCTYPE html>` `<html></html>` `<head></head>` `<meta charset="utf-8">` `<title></title>` and `<body></body>`

5. Metadata influences Search Engine Optimization by providing description to search engines in order to show the webpage to users based on keywords.

6. The `<meta>` tag is used in the `<head>` of the HTML document and depending on what metadata you want to specify you would utilize an attribute for `<meta>`. For an example: `<meta charset="utf-8">` which specifies which characters(think language) the document will utilize.

## How to start to design a website

1. The first step to designing a website is 'Project ideation' which consists of `What exactly do I want to accomplish` `How will a website help me reach my goals?` `What needs to be done, and in what order, to reach my goals`. [source](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Design_and_accessibility/Thinking_before_coding)

2. The most important question to answer when designing a Website is 'What exactly do I want to accomplish?' It is the basis and motivation for the rest of your project(website).

## Semantics

1. You should use an `<h1>` element over a `<span>` element to display a top level heading because it provides more specificity. `<h1>` elements also are larger (talking about just HTML not including CSS font-size) and provide information on what the goal of the element is not only for the creater of the document but if anyone else is also looking at the code.

2. The benefits of using semantic tags in our HTML are, specificity and ease of use. Sure you can use a whole bunch of `<div>` elements but that won't tell anyone what the role of that element is if they need to change code or identify an element.

## What is JavaScript?

1. Two things that require JavaScript in the browser are: user interactivity with the webpage(buttons, prompts, carousels etc) and Application Programming Interfaces (APIs) which are premade kits that assist programmers with implementing different capabilities onto their own projects.

2. You can add JavaScript to your webpage 2 ways: Internally with the `<script>code you want to utilize with JavaScrpt</script>` inside of your actual HTML Doc. or Externally by creating a script sheet(usually named script.js) and still utilizing the `<script>` tag except this time with an attribute sourcing your new script sheet. `<script src='script.js'></script>`

## Things I want to know more about?

- How do you implement APIs? Where do you find them?

- Two things that require JS question confused me
