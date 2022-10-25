# MAP

>method creates a new array populated with the results of calling a provided function on every element in the calling array.

* creates a new array from calling a function for every array element

* calls a function once for each element in an array

* does not execute the function for empty elements

* does not change the original array

```javascript
const numbers = [65, 44, 12, 4];
const newArr = numbers.map(myFunction)

function myFunction(num) {
  return num * 10;
}
```
