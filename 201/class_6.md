Readings:
# Problem Domain, Objects, and the DOM
Below you will find some reading material, code samples, and some additional resources that support the topic for this class and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading
# JavaScript Object Basics

## How would you describe an object to a non-technical friend you grew up with?

_An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects). Variables are containers to keep 'stuff' and functions are methods we use to 'do something' with the properties (contents) in the variable._

## What are some advantages to creating object literals?
_Object literals are commonly used data-structures in js. Convenience, flexibility in declaration and less code during declaration. A object literal can be introduced anywhere in a program with no previous setup and it will work. Very useful._

## How do objects differ from arrays?


Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.


Evaluate the code below. What does the term this refer to and what is the advantage to using this?
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

# Introduction To The DOM

## What is the DOM?
DOM - Document Object Mode is a programming interface for web documents.

## Briefly describe the relationship between the DOM and JavaScript.
DOM allows to change contents and design on structure via js.

Bookmark and Review
Understanding the problem domain is the hardest part of programming

What’s the difference between primitive values and object references in JavaScript?