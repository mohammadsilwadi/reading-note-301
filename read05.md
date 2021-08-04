# Putting it all together
* [reading-note-301](https://mohammadsilwadi.github.io/reading-note-301/)
## React Docs - thinking in React

### How would you break a mock into a component heirarchy?

The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names.

![COMPARISON OPERATORS](https://reactjs.org/static/eb8bda25806a89ebdc838813bdfa3601/6b2ea/thinking-in-react-components.png).

You’ll see here that we have five components in our app. We’ve italicized the data each component represents.

    FilterableProductTable (orange): contains the entirety of the example
    SearchBar (blue): receives all user input
    ProductTable (green): displays and filters the data collection based on user input
    ProductCategoryRow (turquoise): displays a heading for each category
    ProductRow (red): displays a row for each product

### What is the single responsibility principle and how does it apply to components?

 The single-responsibility principle (SRP) is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.

### What does it mean to build a ‘static’ version of your application?

 Static applications and websites render in the user's browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies.

### Once you have a static application, what do you need to add?

make your UI interactive,
React achieves this with state

### What are the three questions you can ask to determine if something is state?

+ Is it passed in from a parent via props? If so, it probably isn’t state.
+ Does it remain unchanged over time? If so, it probably isn’t state.
+ Can you compute it based on any other state or props in your component? If so, it isn’t state.

### How can you identify where state needs to live?

For each piece of state in your application:

+ Identify every component that renders something based on that state.
+ Find a common owner component (a single component above all the components that need the state in the hierarchy).
+ Either the common owner or another component higher up in the hierarchy should own the state.
+ If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
