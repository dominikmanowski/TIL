# object Object

The default conversion from an object to string is "[object Object]".

```javascript
const obj = {"key": "value"}
obj.toString() // -> "[object Object]"
```

To convert an object to its string representation, you can use `JSON.stringify()`.