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

### String

**String Contatenation**

'Hello ' + ' World'

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





**Comparison**

* == 

* !=

* === 

* &&

* ||

