## Return Negative

```js
function makeNegative(num) {
  
  if(num < 0 || num === 0)
      return num
  else{
    return num * -1
  }
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let total = 0
  for(let i =0;i<arr.length;i++){
    if(arr[i]>0){
      total += arr[i]
    }
  }
  return total;
}
```

## Function 2

```js
function square(num) {
  return num * num;
}
```

## Sum Arrays

```js
function sum (numbers) {
    if(numbers === null){
        return 0;}
    else{
      let total = 0; 
        for(let i = 0; i<numbers.length;i++){
          total += numbers[i];
        }
      return total;
    }
};
```

## Reversed Strings

```js
function solution(str){
  let reverseString = ''
  for(let i = str.length;i>0;i--){
    reverseString= reverseString.concat(str[i-1]);
}
  return reverseString;
}
```
