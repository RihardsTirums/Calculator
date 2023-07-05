# 1.Baisic Calculator

## Overview

In this task, you will build a simple command-line calculator using basic TypeScript concepts, including variables and functions. The calculator should be capable of performing basic arithmetic operations like addition, subtraction, multiplication, and division.

<ol>
  <li>Create a New TypeScript File: Create a new TypeScript file named calculator.ts.</li>
  <li>Define Calculator Functions: Your calculator will have four basic operations: addition, subtraction, multiplication, and division. For each operation, define a corresponding function. Each function should take two numbers as parameters and return the result of the operation.
  <br><b>Here's an example for the addition function:</b><br> <img width="331" alt="Screenshot 2023-07-05 at 20 41 51" src="https://github.com/RihardsTirums/Calculator/assets/38011256/055050e5-dc42-479b-aed3-a927f49c561c"></li>
<li>Define the Subtraction Function: Next, create a function to perform subtraction. This function should take two numbers as parameters and return the result of subtracting the second number from the first.</li>
  <li>Define the Multiplication Function: Create a function for multiplication. This function should take two numbers as parameters and return the product of the two numbers.</li>
  <li>Define the Division Function: Finally, create a function to perform division. This function should take two numbers as parameters and return the result of dividing the first number by the second. Don't forget to add a condition that checks if the second number is zero to prevent a divide-by-zero error.</li>
  <li>Create a User Interface: Now that all your calculator functions are defined and tested, it's time to create a user interface. This will be a simple command-line interface that takes user input. Use the built-in readline module in Node.js to take user input. Your interface should prompt the user to input two numbers and to select an operation.</li>
  <li>Test Your Application: Finally, test your full application by running the TypeScript compiler (tsc calculator.ts) followed by node calculator.js in the terminal. Try out all the different operations to ensure they are working correctly together with the user interface.</li>
</ol>

# 2.Calculator Classes and Objects

## Overview

In this task, you'll continue your journey in TypeScript by using classes and objects to build a calculator. This calculator should perform the same functions as your previous calculator but will be designed using object-oriented programming principles.

<ol>
  <li>Create a Calculator Class: Begin by defining a Calculator class in the calculator.ts file.</li>
  <li>Add an Addition Method: Inside your Calculator class, define a method for addition. This should work in a similar way to the add function from the previous task.</li>
  <li>Test the Addition Method: Before you proceed, instantiate the Calculator class and test your add method.</li>
  <li>Add a Subtraction Method: Next, add a subtraction method to your class.</li>
  <li>Test the Subtraction Method: Ensure your subtraction method works as expected by testing it.</li>
  <li>Add a Multiplication Method: Now, add a multiplication method to the Calculator class.</li>
  <li>Test the Multiplication Method: As with the previous methods, be sure to test the multiplication method.</li>
  <li>Add a Division Method: Lastly, add a division method to your class. Remember to include the divide-by-zero error prevention.</li>
  <li>Test the Division Method: Test your division method to ensure it functions correctly.</li>
  <li>Modify the User Interface: Now that your Calculator class is complete, adjust your command-line interface to use an instance of the Calculator class for calculations instead of the individual functions.</li>
  <li>Test Your Application: Finally, test your entire application by running the TypeScript compiler (tsc calculator.ts) followed by node calculator.js in the terminal. Try out all the different operations to ensure they are working correctly with the user interface.</li>
</ol>
