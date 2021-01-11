# Day 16
__1/4/21__

## What are some of the signs and causes of callback-hell?
Callback-hell can often be found when chaining promises together, or in general having bad coding habits. Some causes may be lack of clean code and errors.

## What does the asynchronous code mean and how are callbacks involved?
Asynchronous code means it's code that will take time to process usually it makes a call to an external api or source. Callbacks are the idea that this code will run but will come back as soon as it's finished loading, therefore avoiding only running that snippet of code. 

## Summarize the three ways to avoid callback-hell?
Keep your code shallow - Name all of your functions and have them follow a straight forward approach so it's easier to read and isn't just a block of chaining. 

Modularize - follow a design pattern or have multiple single responsibility documents rather then just one giant one.

 Handle every single error - When coding address every error as you go rather then moving on, also make sure to set up functions or catches to find any potential issues.