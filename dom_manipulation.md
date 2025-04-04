# DOM Manipulation

## Selecting Elements
```js
let heading = document.getElementById("title");
console.log(heading.textContent);
```

## Modifying Elements
```
heading.textContent = "New Title";
heading.style.color = "blue";
```

## Creating Elements
```
let newElement = document.createElement("p");
newElement.textContent = "Hello, World!";
document.body.appendChild(newElement);
```

🌐 Further Reading
[MDN: DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)
