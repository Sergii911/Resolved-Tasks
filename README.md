# Solved Tasks

## Training JS #1: create your first JS function and print "Helloworld!"
https://www.codewars.com/kata/571ec274b1c8d4a61c0000c8
```javascript
function helloWorld(){
  var str = 'Hello World!';
  console.log(str);
  return str;
}
```
## Function 1 - hello world
https://www.codewars.com/kata/523b4ff7adca849afe000035
```javascript
function greet() {
    return "hello world!";
}
```
## Breaking chocolate problem
https://www.codewars.com/kata/534ea96ebb17181947000ada/solutions/javascript/me/best_practice
```javascript
function breakChocolate(n,m) { 
if( n ===0|| m ===0) return 0;
  return m * n -1;
}
````
## Miles per gallon to kilometers per liter
https://www.codewars.com/kata/557b5e0bddf29d861400005d/solutions/javascript/me/best_practice
```javascript
function converter (mpg) {
  return +(mpg*1.609344/4.54609188).toFixed(2)
}
````
## Beginner Series #2 Clock
https://www.codewars.com/kata/55f9bca8ecaa9eac7100004a/solutions/javascript/me/best_practice
```javascript
function past(h, m, s){
  return 3600000 * h + 60000 * m + 1000 * s;
}