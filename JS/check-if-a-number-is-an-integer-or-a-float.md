# How to check if a number is an integer or a float?

Check for a remainder when dividing by 1.

```javascript
const intOrFloat = (n) => {
  if (typeOf n !== "number") return `${n} is not a number`
  if (n % 1 === 0) return `${n} is an integer`
  if (n % 1 !== 0) return `${n} is a float`
}
```