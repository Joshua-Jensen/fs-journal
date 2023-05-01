# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
a namespace is the way select the classes from different files 
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
structs are lighter versions of clases without some of the things like constructors 
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
a task
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
the type that is returned by the function
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
the class from being instantiated on its own
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
it means the return type can be overwritten
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
private 
public 
protected
internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only things inside the class have access it
```