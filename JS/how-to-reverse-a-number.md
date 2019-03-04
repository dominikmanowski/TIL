# How to reverse a number in JavaScript

```javascript
const reversedNum = num => parseFloat(num.toString().split('').reverse().join('')) * Math.sign(num)
```

* `.toString()` - converts the given number into a String. We do this so we can use the split function on it next.
* `.split('')` converts the String into an Array of characters. We do this so we can use the Array reverse function (which does not work on a String).
* `.reverse()` reverses the order of the items in the array.
* `.join('')` reassembles the reversed characters into a String.
* `parseFloat(num)` converts num into a float from a String.
* ` * Math.sign(num)` multiplies the number with the sign of the original number provided

Source: [How to reverse a number in JavaScript – freeCodeCamp.org](https://medium.freecodecamp.org/js-basics-how-to-reverse-a-number-9aefc20afa8d)