# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Similiar to a scope so your files can refer to each other.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are value type while classes are reference and should be used if you plan to have immutable data.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
The new keyword will instantaite a new class of that object type.
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
The access modifier is the public keyword.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The start method will return a string.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The Car class from being instantaited.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Allows the method to be overridden by any class that instantiates it.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, internal.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
They are only accessible from the body of that class or method.
```