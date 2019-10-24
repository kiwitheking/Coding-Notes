# substring()

```Javascript
var str= "Hello TecAdmin!";
var newStr = str.substring(0, str.length - 1);

out=>Hello TecAdmin
```
# slice()
```Javascript
var str = "Hello TecAdmin!";
var newStr = str.slice(0, -1);

out=>Hello TecAdmin
```
# Math.floor()
```Javascript
var a = Math.floor(0.60);
var b = Math.floor(0.40);
var c = Math.floor(5);
var d = Math.floor(5.1);
var e = Math.floor(-5.1);
var f = Math.floor(-5.9);

out=>
0
0
5
5
-6
-6
```
# Math.random()
Return Value:	A Number, representing a number from 0 up to but not including 1

```javascript
Math.floor((Math.random() * 100) + 1);
```
return value from 1 to 100

# indexOf()
Syntax : string.indexOf(searchvalue, start)  
```js
var str = "Hello world, welcome to the universe.";
var n = str.indexOf("we", 5);
```
Looking for we started 5th index

# Destructuring
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment
```
[a, b] = [10, 20];

console.log(a);
// expected output: 10

console.log(b);
// expected output: 20

[a, b, ...rest] = [10, 20, 30, 40, 50];

console.log(rest);
// expected output: [30,40,50]

var o = {p: 42, q: true};
var {p: foo, q: bar} = o;
 
console.log(foo); // 42 
console.log(bar); // true
```
