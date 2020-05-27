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

Math.floor() takes a decimal number, and rounds down to the nearest whole number

```
Math.floor(Math.random() * 50);
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

