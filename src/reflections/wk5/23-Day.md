# Day 17
__1/13/21__

## In simple terms what is a sub doc?
Documents nested inside other documents, they are easily identified by multiple schemas. Mongoose allows sub docs to be used by nesting schemas.
## When might you use a sub doc?
A sub doc is helpful when dealing with a subject that requires multiple objects such a character in a fighting game. 
## How do you add to a collection of sub docs? How about edit them?
To add subdocs later you simply call teh object and create a new subdoc, for example you call the character ryu and make a new move. The best way to edit is to run a find() and then update the array and save. 

link to project: 