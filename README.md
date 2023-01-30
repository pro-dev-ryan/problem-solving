# problem-solving

```javascript
const rotateLeft = (arr, number) => {
  return [...arr.slice(number), ...arr.slice(0, number)];
};
const array = [1, 2, 3, 4, 5];
const result = rotateLeft(array, 4);
console.log(result);


```
