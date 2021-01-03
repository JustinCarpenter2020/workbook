# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
encapsulation, abstraction, inheritance, polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff[name] = property 
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
It's the idea of taking all the data that'll work together and bundling that data together, it helps maintain simplicity and a rule of single purpose.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
single-responsibility
```
**5.** What is the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
a class is a data type, while a instance of a class is an object that fits within that data type.  
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is meant to be a bridge between the code that is kept private and the one the user can use. They tend to grab a piece of information from the private section and make it public. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose of the MVC pattern is to both keep our data safe by only letting the user access only what they need for the program. And also keeps code clean and more efficient. 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
To interact with the DOM
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
To preform business logic
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
To demonstrate what a single instance of that object is, it defines the object and also tends to be where html is injected. 
```

