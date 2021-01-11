# Day 17
__1/5/21__

## What are the three states of a promise?
Pending: This stage is where a promise has not succeeded or failed but is waiting to become one or the other.

Resolved: A completed promise

Rejected: A failed promise 
## how do promises seek to fix the problem of callback-hell?
Promises allow multiple callbacks to be done by chaining promises together. This way was more effective then just callbacks because there was less syntax and it was more easily readable.

## What is the difference between .then() and .catch()?
.then() is for completed promises, so if the promise is accepted that piece of code will execute.
.catch() is for failed promises, if the process fails then catch() will catch the error. 
