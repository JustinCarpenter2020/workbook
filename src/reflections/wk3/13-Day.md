# Day 13
__12/15/20__

## what are the two common operations that we will set in the handler
Get is a common operator that would be set in the handler. Another common is just a basic object operation. 
## What do have to make sure you are doing with every Get to insure the value does not become undefined
We have to use a custom override such as a trap. A trap allows anytime a value is set it will keep the value being modified as well as the value being set.

## What are some of the benefits of the proxy object that we are using in our structure of application?
It allows us to access objects that are private, and use that information. It essentially allows us to pull information from the private and use it.