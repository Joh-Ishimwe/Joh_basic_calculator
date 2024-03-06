# Joh_basic_calculator

Joh_basic_calculator is a simple npm package that provides basic mathematical operations such as addition, subtraction, multiplication, and division.

## Installation

To use Joh_basic_calculator in your Node.js project, you can install it using npm:

```bash
npm install joh_basic_calculator
```
for example
```bash
const calculator = require('joh_basic_calculator');

// Addition
const sum = calculator.add(5, 3);
console.log('Sum:', sum);

// Subtraction
const difference = calculator.subtract(8, 4);
console.log('Difference:', difference);

// Multiplication
const product = calculator.multiply(2, 6);
console.log('Product:', product);

// Division
try {
  const quotient = calculator.divide(10, 2);
  console.log('Quotient:', quotient);
} catch (error) {
  console.error('Error:', error.message);
}
