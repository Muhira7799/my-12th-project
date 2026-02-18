# my-12th-project

Array Operations in JavaScript

This example demonstrates basic array manipulation in JavaScript, including array creation, element access, modification, and iteration.

 Code
// Create an array of fruits
let fruits = ["Apple", "Banana", "Mango", "Orange"];

// Print the whole array
console.log(fruits);

// Print a specific item (index starts from 0)
console.log("First fruit: " + fruits[0]);

// Add a new fruit
fruits.push("Grapes");

// Loop through the array
for (let i = 0; i < fruits.length; i++) {
    console.log("Fruit: " + fruits[i]);
}

 Overview

An array named fruits is initialized with four string elements.

The entire array is printed to the console.

A specific element is accessed using its index (fruits[0]).

A new item is added using the .push() method.

A for loop iterates through the array using its dynamic length property.

▶ Execution Flow

The array is created and stored in memory.

The full array is logged.

The first element (index 0) is accessed and printed.

"Grapes" is appended to the array.

The loop iterates from index 0 to fruits.length - 1, printing each element.

 Concepts Demonstrated

Array declaration and initialization

Index-based element access

Built-in array methods (push)

Looping with for statement

Using the length property

▶ Example Output
["Apple", "Banana", "Mango", "Orange"]
First fruit: Apple
Fruit: Apple
Fruit: Banana
Fruit: Mango
Fruit: Orange
Fruit: Grapes
