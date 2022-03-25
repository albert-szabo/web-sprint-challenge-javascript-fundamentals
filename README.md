# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks. 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results. 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

The .map method does something you tell it to do to each index within an array and then returns a new array with the altered items.
It can be used when you want to update data in an array, but preserve the original data in the original array.
The .reduce method returns one value based on an array by accumulating some value in a variable.
It can be used when you want to some kind of math on indexes in an array, like finding a total or an average.
The .filter method applies a test to each index of an array and only adds those indexes that pass to a new array, which is returned.
It can be used when you want to grab a subset of some original data that has certain values above or below a specified threshold.

2. Explain the difference between a callback and a higher order function.

A callback is a function that is passed to another, separate function as an argument in invoking that separate function. A higher order function is a function that takes other functions as parameters.

3. Explain what a closure is.

A closure occurs when a function goes outside of its own scope to find a variable that is not found there, but is found in a larger / broader / higher level of scope (usually an outer function).

4. Describe the four principles of the 'this' keyword.

In window binding, 'this' returns the window or the global object because it has not been given a narrower, more specific context to use as reference.
In implicit binding, 'this' is used with dot syntax in the context of an object (including with methods) to refer to that specific object.
In explicit binding, 'this' is provided with context to refer to via three special methods: .call, .bind, and .apply.
In new binding, 'this' is provided with context by the 'new' keyword and refers to the new object that is created.

5. Why do we need super() in an extended class?

We need super() in an extended / child class to call the constructor of the parent class and avoid duplication of constructor elements that are common between the two.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your repo to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/master; your codegrade score will update each time you make a push.


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
 
 [Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://bloomtech.notion.site/bloomtech/BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) (see part 2, submitting an assignment with codegrade).
