# Functions in JavaScript

Functions allow code reuse and modularization.

## Function Declaration
```js
function greet(name) {
    return `Hello, ${name}!`;
}
console.log(greet("Alice"));
```

## Arrow Functions
```
const add = (a, b) => a + b;
console.log(add(3, 5));
```

## Function Parameters & Default Values
```
function greet(name = "Guest") {
    console.log(`Hello, ${name}!`);
}
greet(); // Hello, Guest!
```

🌐 Further Reading: [MDN Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
