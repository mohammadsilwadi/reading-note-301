# [reading-note-301](https://mohammadsilwadi.github.io/reading-note-301/)

## Functional Programming Concepts

### What is functional programming?

a programming paradigm where programs are constructed by applying and composing functions

### What is a pure function and how do we know if something is a pure function?

A pure function is a function which: Given the same input, will always return the same output. Produces no side effects.

### What are the benefits of a pure function?

Pure functions are much easier to read and reason about. All relevant inputs and dependencies are provided as parameters, so no effects are observed that alter variables outside of the set of inputs.

### What is immutability?

In JavaScript, only objects and arrays are mutable, not primitive values. (You can make a variable name point to a new value, but the previous value is still held in memory. ... Immutables are the objects whose state cannot be changed once the object is created. Strings and Numbers are Immutable.

### What is Referential transparency?

In functional programming, referential transparency is generally defined as the fact that an expression, in a program, may be replaced by its value (or anything having the same value) without changing the result of the program.

## Node JS Tutorial for Beginners #6 - Modules and require()

### what is a module ?

part of a program that contains one or more routines.

### What does the word ‘require’ do?

used to load and cache JavaScript modules.

### How do we bring another module into the file the we are working in?

coust name =require('./name of the file')

### How do we bring another module into the file the we are working in?

module.exports=name
