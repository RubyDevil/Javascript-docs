​
# VARIABLES
JavaScript uses the keywords **`var`**, `let`, `const` to declare variables.
> How to create variables: 
> ~~~js
>  var x;
> ~~~
> How to assign a value to variables:
> ~~~js
>  x = 5;
> ~~~
> How to create and assign a value to a variable at the same time:
> ~~~js*emphasized text*
>  var x = 5;
> ~~~


## Arithmetic
| Operator | Description                   |
|----------|-------------------------------|
| +        | Addition                      |
| -        | Subtraction                   |
| *        | Multiplication                |
| **       | Exponentiation                |
| /        | Division                      |
| %        | Modulus (Division Remainder)  |
| ++       | Increment                     |
| --       | Decrement                     |

## Assignment
| Operator | Example |  Same As   |
|----------|---------|------------|
| =        | x = y   | x = y      |
| +=       | x += y  | x = x + y  |
| -=       | x -= y  | x = x - y  |
| *=       | x *= y  | x = x * y  |
| /=       | x /= y  | x = x / y  |
| %=       | x %= y  | x = x % y  |
| **=      | x **= y | x = x ** y |

## Comparison
| Operator | Description                        |
|----------|------------------------------------|
| ==       | equal to                           |
| ===      | equal value and equal type         |
| !=       | not equal                          |
| !==      | not equal value or not equal type  |
| >        | greater than                       |
| <        | less than                          |
| >=       | greater than or equal to           |
| <=       | less than or equal to              |
| ?        | ternary operator                   |

## Logical
Logical operators are used to determine the logic between variables or values.
| Operator | Description    |
|----------|----------------|
| &&       | logical *and*  |
| \|\|     | logical *or*   |
| !        | logical *not*  |


# Data Types

The main data types are:
- boolean
- number
- string
- object (3 kinds):
	- object
	- array
	- date

## Boolean
Booleans can only have two values: `true` or `false`.
```js
 var kitaIsCute = true;
 var kitaIsMeaner = false;
```
## Number
Numbers can be written with or without decimals
```js
 var year = 2023;
 var cash = 475.34;
```
## String
Strings are for storing and manipulating text.
They are written between quotation marks **`" "`**:
```js
 var looks = "She's very cute";
```
To find the length of a string, use the built-in `length` property:
```js
 var name = "Kita";
 name.length			// 4
 "Hello World".length	// 11
```
### Escape Characters
Some special characters will be misinterpreted in the string:
```js
var text = "HTML is a "Programming" Language";
```
To avoid this from happening, you must use the backslash `\` before them:
```js
var text = "HTML is a \"Programming\" Language";
```

