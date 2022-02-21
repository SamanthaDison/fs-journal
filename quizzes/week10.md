# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespace works similarly to 'export' in JS and allows us to access that file in a different file/layer with a 'using' statement.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Classes are reference types whereas structs are value types meaning struct will explicitly store the assigned value. Classes allow for inheritance and the change of reference values whereas structs are immutable.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
public void ...
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
the 'type' of value
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The class may not be instantiated on its own and instead must be abstracted out as an extension of another class
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
A virtual method allows for modification of the string or value and allows for it to be overriden in a derived class
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
It may only be accessed from within that class
```