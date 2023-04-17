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


# Operators
> ## Arithmetic
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

> ## Assignment
| Operator | Example |  Same As   |
|----------|---------|------------|
| =        | x = y   | x = y      |
| +=       | x += y  | x = x + y  |
| -=       | x -= y  | x = x - y  |
| *=       | x *= y  | x = x * y  |
| /=       | x /= y  | x = x / y  |
| %=       | x %= y  | x = x % y  |
| **=      | x **= y | x = x ** y |

> ## Comparison
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

> ## Logical
Logical operators are used to determine the logic between variables or values.
| Operator | Description    |
|----------|----------------|
| &&       | logical *and*  |
| \|\|     | logical *or*   |
| !        | logical *not*  |


# Data Types

The main data types are:
- undefined
- null
- boolean
- number
- string
- object (3 kinds):
	- object
	- array
	- date

Examples:
```js
 var food;               // undefined
 var students = null;    // null
 var kitaIsCute = true;  // boolean
 var money = 476;        // number
 var name = "Kita";      // string
 var pos = {x:2, y:3};   // object
 var numbers = [1,2,3];  // array
 var today = new Date()  // date
```

> ## Boolean
Booleans can only have two values: `true` or `false`.
```js
 var kitaIsCute = true;
 var kitaIsMeaner = false;
```

