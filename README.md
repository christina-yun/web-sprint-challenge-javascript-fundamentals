# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

While all 3 array methods are higher order functions that have been made available to use throughout JavaScript as methods and have built-in loops that are part of their mechanisms, the differences and applications below are what set them apart.
    a. .map:  Returns a new array with data that's been converted according to what you are trying to map over in those functions. Map is used for converting data from its raw state into data that you're trying to get and will return the same number of items with whatever code/conditions are applied to it. A use case for .map would be for normalizing (lowercasing) all characters of strings as a first step before running it through a filter for a search that you don't want to be case sensitive.

    b. .filter: Returns a new array only with data that meets the conditions to the filter -- it'll loop through the entire original array and only push in values to the newly created array that meet the conditions set by what you are filtering for. Filter is used for all kinds of things, but I would say its most obvious use case is a search engine like Google!
    
    c. .reduce: Unlike the other two methods, .reduce does not produce an array and its purpose and output is one single value. It "reduces" all the values in a set down to one value, usually for addition or multiplication. Reduce is especially useful and powerful when distilling data into averages or finding out the total of a given piece of data that you're looking for, e.g. average age of a population or total land area of a state 

2. Explain the difference between a callback and a higher order function.

    A: While callback and higher order functions are related, a higher-order function is a function that receives another function (a callback function) as an argument, and a callback function is a function that is passed in as an argument for a higher order function.

3. Explain what a closure is.

    A closure is any time a function reaches outside of its immediate scope into its parent (or grandparent, etc.) scope to grab a value that was defined there. 

4. Describe the four principles of the 'this' keyword.

    1. Window/Global Object Binding:  If 'this' is applied within only the global scope, it will refer to the window/console Object. If this happens, not only is it an error as the program doesn't know what 'this' is referring to, but because it doesn't know, it returns the entirety of JavaScript to the console in its attempt guess what the programmer meant by 'this'.

    2. Implicit Binding: Whenever there is a dot before a called function, the object to the left of that dot is what 'this' is referring to. It will refer to whatever object it is enclosed in.

    3. New Binding: When using a constructor function, 'this' refers to the specific instance of the object that is created and returned by that function. 

    4. Explicit Binding: Whenever we use JavaScript's .call or .apply method 'this' explicitly defines what object 'this' is referring to. 

5. Why do we need super() in an extended class?

    A: We need to use super() in order to access and call functions on an object's parent. While the 'extend' keyword points to what the parent of a class is, super() is the function that calls and copies over all the functions from the parent class to the child class.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

