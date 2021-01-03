# Day 11
__12/13/20__

## What problem does using exports solve?
It allows the user to only have access to the code that is necessary for the program therefore making it harder to break, and keeping private code private. It also allows for the rule of single purpose to be better followed within the code.

## How does *export* differ from *export default*?
If the programmer needs to export multiple **objects** then they would use just export while export default is often used for a single export. It is also essential named vs unnamed exports, export default being the named.


## What is a benefit of using the module system?
+ It increases overall performance of a program
+ makes debugging and finding issues easier
+ They are executed in strict mode so the strict tag doesn't need to be used
+ Overall organize the code better