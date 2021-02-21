# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace is used for organization and to keep data private.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A struct is a much more limited class that is primarily meant to create objects. 
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Abstract
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The type that will return.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It's preventing the class from being instantiated
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Allows any class that inherits it to override the class. 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, private, internal, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only variables or methods within that same class or method. 
```