# Day 12
__12/14/20__

## What is the purpose of encapsulation?
To bundle data and allow only the methods to access an object within the code. Encapsulation creates more predictable and reliable updates.
## What were some of the problems with closures and the underscore prefix?
Breaking changes, internal properties change more then public ones and therefore if it was even deleted it would not be considered breaking to the program. Another issue is that new developers are unaware of the underscore prefix but may use the properties anyways leading to confusion.  

## How do we create private variables in a ES6 class? Why would you do this?
private variables are available in most browsers and can be implemented with stage-3 feature enabled. This would be done if encapsulation needed to be used but certain information should be private. 