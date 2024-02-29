# Wutti Calculator

Wutti Calculator is a simple Node.js module that provides basic arithmetic operations.

## Installation

You can install the Wutti Calculator module via npm:

```bash
npm install wutti-calculator
```
Please note that you need to have Node.js installed on your machine to use this library.

# Usage

```bash
const calculator = require('wutti-calculator');

console.log(calculator.add(5, 3));      // Output: 8
console.log(calculator.subtract(7, 2)); // Output: 5
console.log(calculator.multiply(4, 6)); // Output: 24
console.log(calculator.divide(10, 2));  // Output: 5

```

## API
add(a, b)
Adds two numbers a and b together.

subtract(a, b)
Subtracts number b from number a.

multiply(a, b)
Multiplies two numbers a and b together.

divide(a, b)
Divides number a by number b.

Throws an error if b is zero.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

