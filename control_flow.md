# Control Flow in JavaScript

Control flow determines the execution sequence of statements.

## Conditional Statements
```js
let age = 18;
if (age >= 18) {
    console.log("You are an adult.");
} else {
    console.log("You are a minor.");
}
```

## Switch Statements
```
let fruit = "apple";
switch (fruit) {
    case "apple":
        console.log("Apples are great!");
        break;
    case "banana":
        console.log("Bananas are healthy!");
        break;
    default:
        console.log("Unknown fruit.");
}
```

## Loops
"for" Loop
```
for (let i = 0; i < 5; i++) {
    console.log("Iteration:", i);
}
```

"while" Loop
```
let i = 0;
while (i < 5) {
    console.log("Iteration:", i);
    i++;
}
```
🌐 Further Reading: [MDN Control Flow]([url](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling))
