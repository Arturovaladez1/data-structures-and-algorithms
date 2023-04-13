# 401 Code Challanges

## Task

Write a function called insertShiftArray which takes in an array and a value to be added. Without utilizing any of the built-in methods available to your language, return an array with the new value added at the middle index.

## Code

et newArr = [];

function insertShiftArray(arr, val){
  let middleId = (arr.length/2);
  for(let i=0; i<=arr.length; i++){
    if(i < middleId){
      newArr.push(arr[i]);
    }
    else if (i == middleId){
      newArr.push(val);
    } else {
      newArr.push(arr[i-1]);
    }
  }
}
insertShiftArray([2,4,6,-8], 5)
console.log(newArr);

## Whiteboard Challange #2

[WhiteBoardChallange2](/javascript/code-challenges/Array-insert-shift/WhiteBoard2.png)
