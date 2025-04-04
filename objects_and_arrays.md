# Objects & Arrays in JavaScript

## Objects
```js
let person = {
    name: "Alice",
    age: 25,
    greet: function() {
        return `Hello, my name is ${this.name}.`;
    }
};
console.log(person.greet());
```

## Arrays
```
let fruits = ["apple", "banana", "cherry"];
console.log(fruits[1]); // banana
```

### Array Methods
push(), pop(), shift(), unshift(), map(), filter(), reduce()

🌐 Further Reading
[MDN: Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)
[MDN: Arrays](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

