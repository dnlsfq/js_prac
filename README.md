# INTRODUCTION TO JAVASCRIPT

## Data Types

**primitive data types**
* Number : Any number, including numbers with decimals
* String : Any grouping of characters on your keyboard (letters, numbers, spaces, symbols, etc.) surrounded by '' or ""
* Boolean : true or false
* Null :  intentional absence of a value
* Undefined : absence of a value though it has a different use than null
* Symbol : newer feature to the language, symbols are unique identifiers, useful in more complex coding

**compiled data types**
* Object : Collections of related data

**typeof operator**
 to keep track of the data types of the variables
 ```
 const unknown1 = 'foo';
console.log(typeof unknown1); // Output: string

const unknown2 = 10;
console.log(typeof unknown2); // Output: number

const unknown3 = true; 
console.log(typeof unknown3); // Output: boolean
 ```
 
 

### String

**String Contatenation**

'Hello ' + ' World'

**String Interpolation**
```
const myPet = 'armadillo';
console.log(`I own a pet ${myPet}.`);
// Output: I own a pet armadillo.
```


```
let myPet = 'armadillo';
console.log('I own a pet ' + myPet + '.'); 
// Output: 'I own a pet armadillo.'
```

## Properties
 introduce a new piece of data into a JavaScript program, the browser saves it as an instance of the data type. 
 The . is another operator! We call it the dot operator.
 
 
 i.e.
string instance has a property called length that stores the number of characters in that string. You can retrieve property information by appending the string with a period and the property name

```
console.log('Hello'.length); // Prints 5
```
 
 
## Methods
Remember that methods are actions we can perform
*   a period (the dot operator)
*   the name of the method
*   opening and closing parentheses


i.e.
JavaScript provides a number of string methods.

```
console.log('hello'.toUpperCase()); // Prints 'HELLO'
console.log('Hey'.startsWith('H')); // Prints true
```

## Built-in Objects
like library/framework

to perform more complex mathematical operations than arithmetic, JavaScript has the built-in Math object.

```
console.log(Math.random()); // Prints a random number between 0 and 1

console.log(Math.random() * 50; // generate random number between 0 and 50
```

## Variables

### var
Prior to the ES6, programmers could only use the var keyword
```
var myName = 'Arya';
console.log(myName);
```
### let
the let keyword was introduced in ES6. The let keyword signals that the variable can be reassigned a different value. 
Another concept that we should be aware of when using let (and even var) is that we can declare a variable without assigning the variable a value
```
let price;
console.log(price); // Output: undefined
price = 350;
console.log(price); // Output: 350
```

### const 

const keyword was also introduced in ES6, and is short for the word constant. Just like with var and let you can store any value in a const variable. The way you declare a const variable and assign a value to it follows the same structure as let and var

> Constant variables must be assigned a value when declared. If you try to declare a const variable without a value, you’ll get a SyntaxError.

> const variable cannot be reassigned because it is constant. If you try to reassign a const variable, you’ll get a TypeError

```
const myName = 'Gilberto';
console.log(myName); // Output: Gilberto
```

### Mathematical Assignment Operators

```
let w = 4;
w = w + 1;

console.log(w); // Output: 5

let x = 20;
x -= 5; // Can be written as x = x - 5
console.log(x); // Output: 15

let y = 50;
y *= 2; // Can be written as y = y * 2
console.log(y); // Output: 100

let z = 8;
z /= 2; // Can be written as z = z / 2
console.log(z); // Output: 4
```

###  Increment and Decrement Operator
The increment operator will increase the value of the variable by 1. The decrement operator will decrease the value of the variable by 1

```
let a = 10;
a++;
console.log(a); // Output: 11

let b = 20;
b--;
console.log(b); // Output: 19
```


* Math

```
Math.floor(Math.random() * 50); // .floor() takes a decimal number, and rounds down to the nearest whole number
```

* Number
```
console.log(Number.isInteger(2017))
```



**Resource**

JavaScript, jQuery and jQuery UI Complete Video Course An Introduction to Front-End Web Development

**Array**

var ArrayExample = [];

**Object**

var ObjectExample = {};



**Conditional Statement**

* 'false': false,null,undefined,"",0,NaN
* 'true': anything , even 'false'

```
function flipCoin(){
    if (Math.random() < 0.5){
        return "Heads";
    } else {
        return "Tails";
    }
}

console.log(flipCoin());
```

**Switch**

```
function simpleSwitch(){
  let productId = 2;
  
  switch(productId){
    case 1:
      console.log('Product 1');
      break;
    case 2:
      console.log('Product 2');
      break;
    default:
      console.log('Unknown Product');
      break;
  }
}
```

* block scope in switch
```
function simpleSwitch(){
  let productId = 2;
  
  switch(productId){
    case 1:{
      let message = 'HL Road Frame';
      console.log(message);
      break;
    }
    case 2:{
      let message = 'Sport 100 Helmet';
      console.log(message);
      break;
    }
    default:{
      let message = 'Mountain Bike';
      console.log(message);
      break;
    }
  }
}
```


*

*Comparison**

* == 

* !=

* === 

* &&

* ||

