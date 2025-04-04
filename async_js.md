# Asynchronous JavaScript

## Callbacks
```js
function fetchData(callback) {
    setTimeout(() => {
        callback("Data received");
    }, 2000);
}
fetchData(console.log);
```

## Promises
```
let promise = new Promise((resolve) => {
    setTimeout(() => resolve("Promise resolved"), 2000);
});
promise.then(console.log);
```

## Async/Await
```
async function fetchData() {
    return "Data received";
}
fetchData().then(console.log);
```

🌐 Further Reading
[MDN: Async JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous)
