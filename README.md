# JavaScript: Handling undefined or null when accessing object properties

This repository demonstrates a common error in JavaScript related to accessing properties of potentially undefined or null objects and offers a solution.

## The Bug
The `bug.js` file contains a function that attempts to access the `length` property of an object.  If the object is null or undefined, a `TypeError` will be thrown.  This is a very common error. 

## The Solution
The `bugSolution.js` file demonstrates the use of explicit null and undefined checks before accessing the `length` property, preventing the error and handling these cases gracefully. 

## How to Run
1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in your preferred JavaScript environment.
3. Run each file to observe the output and the difference in behavior.