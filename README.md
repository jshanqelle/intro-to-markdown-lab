Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

1. Basic syntax

const functionName = (params) => {
  // code to be executed
}

const: const should be used whenever a function expression is assigned to a variable.
The function name: The name you choose for the function.
Parameters: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
The arrow syntax: Indicates that this will be a function.
The body: The statements that make up the function itself. Surrounded by curly braces.

Example:

const greet = (name) => {
  console.log("Hello, " + name + "!");
}

Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

2. Calling a function

To execute the function, you call or invoke it by using its name followed by parentheses.

Example:

greet('Alice'); // Outputs: Hello, Alice!

3. Return values

Functions can process data input and output a value using the return keyword.

Example: 

const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6

For more information on functions and how they are used in JS, check out the MDN docs. 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions


Part 1: Applying Styles in a Markdown

# h1
## h2
### h3
#### h4
##### h5
###### h6


Part 2: Text Styles

-Bold:
This text is **bold**. This text is also __bold__.

-Italic:
This text is in *italics*. This text is also in _italics_.

-Italic and Bold

This text is ***bold and italicized***. This text ia also ___bold and italicized__. 


You do:

const: ...
The function name: ...
Parameters: ...
The arrow syntax: ...
The body: ...

3. Creating lists:
-Bulleted lists:
* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
    * Subitem 2.2.1
-Numbered lists: ordered lists:
1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2

4. Code snippets:
-Inline code;
Use the `console.log()` function to print values to the console.
```javascript
const printItem = (item) => {
  console.log(item);
}
```
const printItem = (item) => {
  console.log(item);
}
you do:
Use the `console.log()` function to print values to the console.

5. Adding links

-Inline-style links:
[Google](https://www.google.com)
This is [a reference][example].

[example]: http://www.example.com/

you do:
[MDN Web Docs](https://developer.mozilla.org/)


6. Blockquotes
-> This is a blockquote.
-> First level of blockquote.
>> Nested blockquote.
>>> Another nested blockquote.

you do:
Markdown automatically handles numbered lists, so you can use `1.` for every item, and it will still display correct numbering.

7. Adding images
-Hosted image embedding:
![some alt text](www.url_to_an_image.com/image)

![Computer with Code](https://images.unsplash.com/photo-1587620962725-abab7fe55159?auto=format&fit=crop&q=80&w=1631&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

![Computer with Code](/modular-curriculum-all-courses/intro-to-markdown-lab/exercise/assets/james-harrison-unsplash.jpg)

![some alt text](www.url_to_an_image.com/image)

![some alt text](./the-name-of-my-image.jpg)

8. Extended syntax