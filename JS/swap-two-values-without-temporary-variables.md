# Swap two values of without temporary variables

You can use ES6 Array Destructuring Assignment

```javascript
let a = 8, b = 6;

(() => {
  [a, b] = [b, a]
})();

console.log(a); // 6
console.log(b); // 8
```