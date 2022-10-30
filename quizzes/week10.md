# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
namespace declares what the type is for the file
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
struct = public. class = private
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
return string
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
virtual
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
what the function wants to return
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
abstract preventing is an attempt to prevent abstract functions from doing the incorrect task
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
base class member derived on the requirement
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
class ctor varible method
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
the functions alone
```