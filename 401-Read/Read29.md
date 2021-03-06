# react I
![rreact](../image/react1.png)

## Template literals
 * Concatenation/string interpolation
Expressions can be embedded in template literal strings.
 * Multi-line strings
Using template literal syntax, a JavaScript string can span multiple lines without the need for concatenation.
 * Implicit returns
The return keyword is implied and can be omitted if using arrow functions without a block body.
 * Key/property shorthand
ES6 introduces a shorter notation for assigning properties to variables of the same name.
 * Method definition shorthand
 * The function keyword can be omitted when assigning methods on an object.
 * Destructuring (object matching)
 * Use curly brackets to assign properties of an object to their own variable.
 * Array iteration (looping)
A more concise syntax has been introduced for iteration through arrays and other iterable objects.
 * Default parameters
Functions can be initialized with default parameters, which will be used only if an argument is not invoked through the function.
 * Spread syntax
Spread syntax can be used to expand an array.
Spread syntax can be used for function arguments.
 * Classes/constructor functions
ES6 introducess the class syntax on top of the prototype-based constructor function.
 * Inheritance
The extends keyword creates a subclass.
 * Modules - export/import
 * Modules can be created to export and import code between files.
 * Promises/Callbacks
Promises represent the completion of an asynchronous function. They can be used as an alternative to chaining functions.
___
## React - Hello World
Hello World
The smallest React example looks like this:
```
ReactDOM.render(
  <h1>Hello, world!</h1>,
  document.getElementById('root')
);
```

## React - JSX
___
Why JSX?
React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.

Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called â€œcomponentsâ€� that contain both.

React doesnâ€™t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.

## React - Rendering Elements
___
To render a React element into a root DOM node, pass both to ReactDOM.render()

## React - Components & Props
___
Components and Props
Components let you split the UI into independent, reusable pieces, and think about each piece in isolation. This page provides an introduction to the idea of components.

Components are like JavaScript functions. They accept arbitrary inputs (called â€œpropsâ€�) and return React elements describing what should appear on the screen.
```
Function and Class Components
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}
```
This function is a valid React component because it accepts a single â€œpropsâ€� (which stands for properties) object argument with data and returns a React element. We call such components â€œfunction componentsâ€� because they are literally JavaScript functions.

## Composing Components
___
Components can refer to other components in their output. This lets us use the same component abstraction for any level of detail. A button, a form, a dialog, a screen: in React apps, all those are commonly expressed as components.

___