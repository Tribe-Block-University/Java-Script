# Tribe Block JS Tutorial

Welcome to this JavaScript tutorial! This guide is designed to help beginners understand the fundamentals of JavaScript and its key concepts.

## Table of Contents

- [Introduction](#introduction)
- [Setting Up Your Environment](#setting-up-your-environment)
- [JavaScript Basics](#javascript-basics)
  - [Variables](#variables)
  - [Data Types](#data-types)
  - [Operators](#operators)
  - [Functions](#functions)
  - [Control Flow](#control-flow)
- [Working with the DOM](#working-with-the-dom)
- [Event Handling](#event-handling)
- [Asynchronous JavaScript](#asynchronous-javascript)
- [References](#references)

## Introduction

JavaScript is a versatile, high-level programming language primarily used for web development. It enables interactive web pages and is an essential technology alongside HTML and CSS.

## Setting Up Your Environment

To start coding in JavaScript, you need:

1. A text editor (VS Code, Sublime Text, etc.).
2. A web browser with Developer Tools (Chrome, Firefox, etc.).
3. Node.js (optional for backend JavaScript development).

## JavaScript Basics

### Variables

JavaScript supports three ways to declare variables:

```js
var name = "John"; // Function-scoped
let age = 25; // Block-scoped
const PI = 3.14; // Constant, block-scoped
```

### Data Types

JavaScript has several data types:

- Primitive: `string`, `number`, `boolean`, `null`, `undefined`, `symbol`, `bigint`
- Non-primitive: `object`, `array`, `function`

### Operators

Common operators in JavaScript:

```js
let sum = 5 + 10; // Arithmetic operators
let isEqual = 5 === "5"; // Comparison operators
let logicalAnd = true && false; // Logical operators
```

### Functions

Functions allow reusable blocks of code:

```js
function greet(name) {
    return `Hello, ${name}!`;
}
console.log(greet("Alice"));
```

### Control Flow

Conditional and loop structures:

```js
if (age > 18) {
    console.log("Adult");
} else {
    console.log("Minor");
}

for (let i = 0; i < 5; i++) {
    console.log(i);
}
```

## Working with the DOM

The Document Object Model (DOM) allows JavaScript to manipulate HTML content dynamically.

```js
document.getElementById("demo").innerText = "Hello, JavaScript!";
```

## Event Handling

JavaScript enables interactive behavior by responding to user actions.

```js
document.querySelector("button").addEventListener("click", () => {
    alert("Button Clicked!");
});
```

## Asynchronous JavaScript

Handling asynchronous operations using Promises and async/await:

```js
async function fetchData() {
    let response = await fetch("https://api.example.com/data");
    let data = await response.json();
    console.log(data);
}
```

## References

For more in-depth details, check out the official documentation:

- [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [JavaScript Info](https://javascript.info/)

---

Happy Coding! 🚀
