## 1 task

Example:

```javascript
var makeFunction = function () {
    var addOne = function (x) {
        return x + 1;
    };
    return addOne; // return the function
};
// makeFunction is a function with no arguments

var f = makeFunction();
// f is a function that takes one argument

var y = f(3);
// now y is 4
```

Create a function that will always return a number multiply on 3!

Write a JavaScript program to calculate the factorial of a number using 1 task, but ask user for a number to get factorial from using prompt() function.

Then give an answer to user after calculation is finished using console.log(number);

## 2 task

Make this syntax possible: var a = add(2)(3); //5

```javascript
var add = function () {
    // your code
};

console.log(add(2)(3)); // 5

```

## 3 task 

Transform array of numbers to array of functions that will console.log and return that digits:

```javascript
 
var numberArray = [1, 2, 3, 4, 10, 5, 6, 7];

// in result we will have: [function (){...}, function (){...}, function (){...}, function (){...}]
```

## 4 task 

Please write a function "double" and "doublePLusFive" so the following code will be true.
To create a "doublePLusFive" function please use double function inside.

```javascript
 double(9); // 18
 double(3); // 6
 
 doublePLusFive(3); // 18 = 3 * 2 + 5
 doublePLusFive(2); // 12 = 2 * 2 + 5
 doublePLusFive(5); // 30 = 5 * 2 + 5
```

## 5 task 

Please write a function "makeCount" so the following code will be true.

```javascript
function createCount () {
// your code here
}

var makeCount = createCount();

makeCount(); // 1
makeCount(); // 0
makeCount(); // 1
makeCount(); // 0
makeCount(); // 1
makeCount(); // 0

```

## 6 task 

Please write a function "makeCount" so the following code will be true. Use the previous function.

```javascript
function createCount (startFrom) {
}

var makeCount = createCount(4);

makeCount(); // 5
makeCount(); // 6
makeCount(); // 7
makeCount(); // 8
makeCount(); // 9
makeCount(); // 10

```
