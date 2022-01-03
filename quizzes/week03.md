# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, Abstraction, Inheritance, and Polymorphism
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
const handler = {
  get(target, property{
    return property
  })
}
const proxyStaff = new Proxy(staff, handler)

```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is way of hiding data and functions in individual states.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
'Single Responsibility': code should be simple and functions should be specific
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class defines the properities or attributes of an object, and an instance is a new object created with the prescribed properties.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is like a copy of another object which can be redefined and 'intercepted'
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The MVC pattern allows for more manipulation to the DOM by the user. It also allows the developer to 'hide' their code and functions. Using the MVC creates a 'blue-print' which can be built and manipulated.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller stores functions that are intereacted with by the user within the DOM
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service manipulates data within the AppState
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The Model stores classes for our objects to then be instanced and manipulated by the service. 
```
