// script.js
// Author: Hellen Beatrice Apolot
// Date: 01/06/2026
// Description: Demonstrates JavaScript functions, recursion, arrays, exceptions, and use of a library

// 1. Display output to the screen
document.getElementById("output").innerHTML = "<p>Hello from JavaScript!</p>";

// 2. Native Array ES6 functions
const numbers = [1, 2, 3, 4, 5];
const doubled = numbers.map(n => n * 2);
console.log("Doubled numbers:", doubled);

// 3. Recursion
function factorial(n) {
  if (n === 0) return 1;
  return n * factorial(n - 1);
}
console.log("Factorial of 5:", factorial(5));

// 4. Throwing and handling exceptions
function divide(a, b) {
  if (b === 0) {
    throw new Error("Division by zero is not allowed!");
  }
  return a / b;
}

try {
  console.log(divide(10, 0));
} catch (error) {
  console.error("Caught an error:", error.message);
}

// 5. Using a JavaScript library (Lodash via CDN)
const script = document.createElement("script");
script.src = "https://cdn.jsdelivr.net/npm/lodash@4.17.21/lodash.min.js";
script.onload = () => {
  const shuffled = _.shuffle([1, 2, 3, 4, 5]);
  console.log("Shuffled array using Lodash:", shuffled);
};
document.head.appendChild(script);
