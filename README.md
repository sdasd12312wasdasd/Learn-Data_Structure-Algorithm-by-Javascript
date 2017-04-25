# Learn Data Structure and Algorithms by Javascript

> You need to have basic understanding of the JavaScript programming language to proceed with the codes from this repository.



## Table of Contents
- [Introduction to JavaScript](#introduction)
- [Data Structure](./Data%20Structure/)
  - [Linked List](./Data%20Structure/Linked%20List/)
  - [Stack](./Data%20Structure/Stack/)
  - [Queue](./Data%20Structure/Queue/)
  - [BST](./Data%20Structure/BST/)


- [Searching](./Searching/)
  - [Linear Search](./Searching/Linear%20Search/)
  - [Binary Search](./Searching/Binary%20Search/)
  - [Ternary Search](./Searching/Ternary%20Search/)


- [Sorting](./Sorting/)
  - [Selection Sort](./Sorting/Selection%20Sort/)
  - [Bubble Sort](./Sorting/Bubble%20Sort/)
  - [Insertion Sort](./Sorting/Insertion%20Sort/)
  - [Merge Sort](./Sorting/Merge%20Sort/)
  - [Quick Sort](./Sorting/Quick%20Sort/)

---

## Introduction

JavaScript is a **loosely typed** or a **dynamic language**. That means you don't have to declare the type of a variable ahead of time. The type will get determined automatically while the program is being processed. That also means that you can have the same variable as different types:
```javascript
var foo = 42;    // foo is now a Number
var foo = 'bar'; // foo is now a String
var foo = true;  // foo is now a Boolean
```

### Data Types in JavaScript
The latest ECMAScript standard defines seven data types:

- Six data types that are primitives:

  - Boolean (`true` and `false`)
  - Null (invalid object or address has the value `null`)
  - Undefined (a variable that has not been assigned a value has the value `undefined`)
  - Number (integer and floating point values ranging from  -(2<sup>53</sup> -1) to (2<sup>53</sup> -1), +Infinity, -Infinity and NaN(not-a-number) )
  - String (Sequence of textual characters. Strings are immutable in JavaScript)
  - [Symbol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol) (new in ECMAScript 6)

- [Object](https://www.w3schools.com/js/js_object_definition.asp)

#### Arrays
JavaScript **Arrays** are regular objects for which there is a particular relationship between integer-key-ed properties and the 'length' property. Additionally, arrays inherit from Array.prototype which provides to them a handful of convenient methods to manipulate arrays like indexOf (searching a value in the array) or push (adding an element to the array), etc. This makes arrays a perfect candidate to represent lists or sets.


#### More details about data types in JavaScript:

- [JavaScript data types and data structures - Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)
- [A Beginner’s Guide to JavaScript Variables and Datatypes - SitePoint](https://www.sitepoint.com/beginners-guide-javascript-variables-and-datatypes/)

#### Object Oriented Programming in JavaScript

- [Introduction to Object-Oriented JavaScript - Mozilla Developer Network](https://developer.mozilla.org/ms/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
- [OOP In JavaScript: What You NEED to Know - JavaScript is sexy](http://javascriptissexy.com/oop-in-javascript-what-you-need-to-know/)

### Big-O Cheat Sheet

[Big-O Cheat Sheet Link](http://bigocheatsheet.com/)

### How to Use
The easiest way to run and test the codes from this repository is to use [nodejs](https://nodejs.org/en/) (I have checked my code using nodejs v6.5.0 in an Windows machine).

Install it in your machine and add it to your environment path so that it is accessible in terminal commands.

Then you can run a JavaScript file like this:
```javascript
node file.js
```

### Useful Links:
* [Eloquent JavaScript](http://eloquentjavascript.net/)
* [Speaking JS](http://speakingjs.com/es5/index.html)
* [You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
* [JavaScript - Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Algorithms, 4th Edition (book by: Robert Sedgewick and Kevin Wayne)](http://algs4.cs.princeton.edu/home/)
