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

Map, reduce, and filter are all methods that can be used on arrays. Map will run through each index of the array and run an anonymous function of the coder's design and manipulate each index of the array and return all the new results in an array. A use case would be to multiply each index in teh arry by an amount. Reduce will 'reduce' an array to a single value based on the coder's design. It will run through each index of the array, and perform an operation on each index and a cumulative total (which is a total resulting from performed operations on previous indexes in the same array.) An example would be to figure out the sum total of all the indexes in an array. Filter will return an array filtering based on a condition. For example, taking an array of numbers and returning an array with only the numbers in that array that are greater than 5.

2. Explain the difference between a callback and a higher order function.
A callback function is a function that is being called as an argument in another function. A higher order function is a function that receives a function as an argument. 

3. Explain what a closure is.
A closure exists when a subfunction is created, and it refers to the fact that the subfunction will have access to the scope of its parents' lexiscopes.

4. Describe the four principles of the 'this' keyword.
1.) When used in the global scope, 'this' will refer to the window/console Object
2.) whenever a function is called by a preceding dot (if it is a method) the object left of the dot will be assigned the 'this' ('this' will point to that object and its key/value pairs)
3.) when a constructor function is used, this refers to the specific instance of the object that is created and returned by the constructor function
4.) Explicit binding - when you use .call or .apply you can overwrite what object 'this' will point to.
5. Why do we need super() in an extended class?
Super() allows us to let the child to inherit the parent's constructor and methods (it takes place of using prototypes, for instance)

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

