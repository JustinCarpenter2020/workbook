# CSS Specificity and Pseudo Classes
__12/1/20__

## What is a Pseudo-Class and what are some of the most common ones you think you will use
Pseudo classes are used to define when an element that has a special use or ability. These classes tend to add style or functionality to the property. Some common ones I intend to use are:

1.**Hover** as it seems aesthetically pleasing especially for buttons.

2.**Nth** tags seem to be helpful when searching for a specific number or number of occurrences like odds or evens.

3.**Required** for things like usernames and emails before the webpage can move on.

4.**Root** as it makes code cleaner and more easily readable

## What is Specificity?
Specificity is the css rule that determines what property will be shown when the code is run. It typically works by assigning a number to the code based on how many selectors, classes, and id's it has. The highest number will be the property that shows once the code is finished. 
## how could you use specificity to your advantage? 
Specificity allows for a webpage or application to be designed very intricately and deliberately. With this in mind one could easily target one piece of text for example and color it differently while not effecting the rest of a paragraph it's in. Simply being aware of the concept allows the programmer to easily create and interact with their css and not be confused when something is being overridden by higher specificity. 

## What problems do you think you could run into if you over-utilized the !important feature?
The important feature adds an astronomically high specificity to the css rule it is attached to. Using the tag means that one couldn't easily adjust the css of the code. This could lead to problems editing or presenting the code, if a client wishes to change slightly that attribute it must be done from the html and not the css. Now if the !important tag is scattered throughout the html then adjusting anything from the css sheet will become challenging causing more grief then it's worth for the the dev and their team. Overall, it's a bad practice that disorganizes code and breaks the single responsibility rule for code.


## Helpful Video of The Day

<a href="https://www.youtube.com/watch?v=c0kfcP_nD9E&ab_channel=KevinPowell
" target="_blank"><img src="https://miro.medium.com/max/1200/1*6hHvO7awHiPRZ06gK1syFQ.png"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>