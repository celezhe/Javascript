README
===========================
About the usage of Javascript

****
	
|Author|Ruizhe Huang|
|---|---
|E-mail|celezhe@umich.edu

## Print
console.log()

## Operator

###
== means checking the equality through implicit conversion
###
=== means checking the equality of both type and data

## Truthy and Falsy
### Truthy
If it's not falsy, then it's truthy
### Falsy

* Boolean value false
* null type
* undefined type
* number 0
* empty string ""
* odd value NAN meaning not a number

## Tenary Operator
### Example
var color = isGoing ? "green" : "red";

## Switch
### Example
###
switch(option){
###
    case1:
###
    case2:
###
}
###
Similar to what we did in C++


## Function
### Example
function reversestring(stri) {
}

###
Note: **parameters** are variables that are used to store the data that's passed into a function for the function to use. **Arguments** are the actual data that's passed into a function when it is invoked.

## Global Scope and Function Scope
Global variable is outside all the function.

## Hoisting
###
Before the program is executed, all functions are hoisted to the top of their current scope.
###
The variable declarations is also going to be hoisted at the top of its scope.
