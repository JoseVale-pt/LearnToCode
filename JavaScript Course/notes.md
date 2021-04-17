// Variables
var firstName = 'Vale';
console.log(firstName);
firstName = 'Jose';
console.log(firstName);

//Types of variables

// String var examples
var username ='';
var email = 'josevale.pt@gmail.com'

// Numeric var examples
var a = -1;
var b = 0;
var c = 100;
var average = 1.98;

// Boolean var examples
var javaScriptIsAwesome = true;
var pythonIsAwesome = false;

// Object var examples
var person = {
    firstName: 'Terry',
    lastName: 'Jones',
    age: 32,
};

var anotherPerson = {
    firstName: 'John',
    lastName: 'Smith',
    age: 22,
    address: {
        line1: '1 high Street',
        city: 'London',
        countryId: 51,
    },
};

// Undefined
var country;

// null
var nothing = null;
var animal = 'Hippo';
animal = null;

// Math Examples
var a = 5;
var b = 7;
var result = a + b;
console.log(result);

// More Math Examples
var values = (0.9, 4.8, 1.5);
var min = Math.min(0.9, 4.8, 1.5);
var max = Math.max(0.9, 4.8, 1.5);
console.log('Min:', min, Math.floor(min));
console.log('Max:', max, Math.ceil(max));

console.log(Math.floor(Math.random()*10));

var greeting ='Hello';
console.log(greeting.toUpperCase());

var part1 = 'Javascript';
var part2 = 'is';
var part3 = 'cool';
var message = part1 + ' ' + part2 + ' ' + part3;
console.log(message.toUpperCase());

// Exercice 1
var a = '10';
var b= '5';
var c = '20';
var d = '30';

var result;
result = ((Number(a) + Number(b) + Number(c) + Number(d)) / 4);
console.log(Math.ceil(result));

var randomDieRollOutcome = Math.random() * 6;
console.log(Math.ceil(randomDieRollOutcome));