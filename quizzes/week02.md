# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
``` var, let, const

```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
``` A set of statements or acts that will calculates a value. Requires a parameter and argument.

```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility; open-closed; liskov substitution; interface segregation; dependency inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```Index 2; arrays begin with index 0

```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
Creat a new array or dictionary and add both to them. 
Let newArray = object.assign ([], you, them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```if (1 > 0){
  return :true
}

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
Iterator; i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for document object model; HTML is the first file accessed.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Boolean, Null, Undefined, Number, BigInt, String, Symbol
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is the variable or 'key' being plugged into the function in order to execute the argument or conditions of a function. Parameter goes in; and arguments are the conditions expressed.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values are fixed and stored on the stack; reference values are dynamic and stored on the heap.
```