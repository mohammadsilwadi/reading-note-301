# React Docs - lists and keys

## What does .map() return?

It returns a new array and elements of arrays are result of callback function

## If I want to loop through an array and display each value in JSX, how do I do that in React?

using map() method  

## Each list item needs a unique ____

key

## What is the purpose of a key?

The key prevents relative rotation between the two parts and may enable torque transmission.
Keys are defined to speed up access to data and, in many cases, to create links between different tables.

# The Spread Operator

## What is the spread operator?

 The spread operator is commonly used to make shallow copies of JS objects. Using this operator makes the code concise and enhances its readability.

## List 4 things that the spread operator can do

 +Copying an array.
+Concatenating or combining arrays.
+Using Math functions.
+Using an array as arguments.



## Give an example of using the spread operator to combine two arrays.
1-
const firstName = {firstName: "mohammad"}
const lastName = {lastName: "silwadi"}
const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "mohammad", world: "silwdi" }

2-
const firstName = ['mohammad','ahmad','ali']
const Names = [...firstName];
console.log(Names) // Array(3) [ 'mohammad','ahmad','ali' ]
fruits[0] = 'silwadi'
console.log(...[...firstName,...Names]) //  silwadi ahmad ali = ... mohammad ahmad ali 

## Give an example of using the spread operator to add a new item to an array.
const firstName = ['mohammad','ahmad','ali']
const moreNames = ['silwadi', ...fewFruit]
console.log(fewMoreFruit) //  Array(4) [ "mohammad", "ahmad", "ali", "silwadi" ]

## Give an example of using the spread operator to combine two objects into one.
let person = {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356'
};


let job = {
    jobTitle: 'JavaScript Developer',
    location: 'USA'
};

let employee = {
    ...person,
    ...job
};

console.log(employee);

>>>> output {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356',
    jobTitle: 'JavaScript Developer',
    location: 'USA'
}

# How to Pass Functions Between Components
## In the video, what is the first step that the developer does to pass functions between components?
increment function
## In your own words, what does the increment function do?
update the state


## How can you pass a method from a parent component into a child component?
from the button

## How does the child component invoke a method that was passed to it from a parent component?

through props. 