# The console dollars

## `$0` 

`$0` is a is a reference to the currently selected html node in the Elements tab in DevTools.

Element selected previously is under `$1`, `$2` the one before that, etc. up to the number `$4`.

## `$` & `$$`

`$` == `document.querySelector`

`$$` == `document.QuerySelectorAll` and returns an array of nodes instead of NodeList type.
* `$$('div')` === `Array.from(document.querySelectorAll('div'))`

## `$_`

`$_` references the result of the last evaluated expression

```javascript
Math.random() // 0.6442681496515175
$_ // 0.6442681496515175
```