### Variables
```js
// var variable
// - generic variable
// - can be re-assigned.
var name = 'John Smith';

// let variable
// - generic variable
// - can be re-assigned.
// - cannot begin with a number
let name = 'John Smith';


// const variable
// - constant variable
// - cannot be re-assigned
const name = 'John Smith';
```

### Data Types

```js
// Primative Data Types
// - String
let str = 'hello';

// - Number
let num = 5;

// - Boolean
let isValid = true;

// - Null
let name = null;

// - Undefined
let address;


// Refernce Data Types
// - Arrays
let colours = ['red', 'green'];

// - Object Literals
let person = {
    name: 'John'
    age: 20
};

// - Functions
function findPerson() {
    // find person logic
};

// - Date
let date = new Date();
```

### Type Conversions
```js
// Strings conversions
let str1 = new String(8);

let str2 = new String(true);

let str3 = new String(new Date());

let str4 = (8).toString();

let str5 = (true).toString();

let str6 = (new Date()).toString();

// Number conversions

let num1 = new Number(true);

let num2 = parseInt('100.30');

let num3 = parseFloat('100.30');

let num1 = new Number(5).toFixed(2);

```

### Math and Numbers

```js
Math.PI; // Pi value

Math.E; // Eulers

Math.round(2.8); // 3

Math.ceil(2.8); // 3

Math.floor(2.8); // 2

Math.sqrt(64); // 8

Math.abs(-6); // 6

Math.pow(8, 2); // 64

Math.min(2, 44, 55, 3223, 8); // 2

Math.max(2, 44, 55, 3223, 8); // 3223

Math.random(); // random decimal
```

### String Methods

```js
const firstName = 'John';
const lastName = 'Smith';
const colours 'blue, green, red, yellow';

name.length; // 4

firstName.concat(' ', lastname); // John Smith

firstName.toUpperCase(); // JOHN
firstname.toLowerCase(); // john

firstName[0]; // J

firstName.indexOf('J'); // 0

firstName.chatAt(firstName.length-1); // n

firstName.substring(0, 3); // John

firstName.slice(0, 3); // John

colours.split(', '); // array with 4 elements

colours.replace('yellow', 'purple'); // 'blue, green, red, purple'

colours.includes('red'); // true
```

### Template Literals
```js
const name = 'John;'
const age = 20;
const job = 'Software Engineer';
const city = 'New York';

// use back ticks and interpolation syntax
let bio = `Name: ${name}, Age: ${age}, Job: ${job}, City: ${city}.`;
```

### Arrays 

```js
let numbers = [43, 56, 66, 8];

let numbers = new Array(43, 56, 66, 8);

numbers.push(222); // adds to back of array

numbers.unshift(120); // adds to front of array

numbers.pop(); // removes last element of array

numbers.shift(); // removes first element of array

numbers.splice(1,2); // removes elements in range by index

numbers.reverse(); // reverses array

numbers.concat(new Array(43, 56)); // joins arrays

numbers.sort(); // sorts by alphabetical or ascending order

numbers.find(function () { // filtering
    return num < 50;
}); 

```

### Object Literals
```js

```

