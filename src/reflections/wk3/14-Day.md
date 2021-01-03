# Day 14
__12/16/20__

## What problems does the observer pattern seek to solve?
It seeks to make more code reusable code, this code solves the specific needs of the developer while being broad enough for multiple uses.
## What are the three mechanisms of the observer pattern?
1\. The subscribe method: Grabs a list of observed events and pushes a new item into the array

2\. The unsubscribe method: Uses the filter action to go through the array and remove only the desired item from the array.

3\. The broadcast method: goes through the list of observed events and executes all callbacks.
## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom?
The template uses the MVC pattern through imports and exports to make the code easier to follow and understand while still keeping specific data private. Proxy objects are used when we need to access a private piece of data to display it to the user. Models make the definitions for these objects, controllers update the DOM, and service provides the logic. Everything has a single purpose for the most part making debugging much easier. 