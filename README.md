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
````
## Find the Slope
https://www.codewars.com/kata/55a75e2d0803fea18f00009d/solutions/javascript/me/best_practice
```Javascript
function slope(points){ 
if ((points[0]-points[2]) !== 0){
return ((points[1]-points[3])/(points[0]-points[2])).toFixed(0);;
} else return 'undefined'; 
}
````
## Grasshopper - Basic Function Fixer
https://www.codewars.com/kata/56200d610758762fb0000002/solutions/javascript/me/best_practice
```Javascript
function addFive(num) {
  var total = num + 5;
  return total;
}
```
## Grasshopper - Basic Function Fixer
https://www.codewars.com/kata/56200d610758762fb0000002/solutions/javascript/me/best_practice
```Javascript
function addFive(num) {
  var total = num + 5;
  return total;
}
```
## Basic data types--Number
https://www.codewars.com/kata/571edd157e8954bab500032d/solutions/javascript/me/best_practice
```javascript
var v1=50;v2=100,v3=150,v4=200,v5=2,v6=250
function equal1(){
  var a=v1   
  var b=v1   
  return a+b;
}
//Please refer to the example above to complete the following functions
function equal2(){
  var a=v4;   //set number value to a
  var b=v2;   //set number value to b
  return a-b;
}
function equal3(){
  var a=v1;   //set number value to a
  var b=v5;   //set number value to b
  return a*b;
}
function equal4(){
  var a=v4;   //set number value to a
  var b=v5;   //set number value to b
  return a/b;
}
function equal5(){
  var a=v6;   //set number value to a
  var b=v3;   //set number value to b
  return a%b;
}
```
## For Twins: 2. Math operations
https://www.codewars.com/kata/59c287b16bddd291c700009a/solutions/javascript
```javascript
function iceBrickVolume(radius, bottleLength, rimLength) {
  return  (2 * Math.pow(radius, 2)) * (bottleLength - rimLength)
}
```