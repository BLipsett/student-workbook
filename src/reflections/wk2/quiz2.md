# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?

<!-- enter you answer in the space below -->

```
let, var, const
```

**2.** What is the definition of a function?

<!-- enter you answer in the space below -->

```
A set of statements that performs a task.
```

**3.** What are the `SOLID` principles?

<!-- enter you answer in the space below -->

```
Single responsibility principle - classes do one thing.
Open closed principle - objects should allow for more but not break whats there.
Liskov substitution principle
Interface segregation principle - functions should only do one thing
Dependency Inversion principle - higher level functions shouldnt depend on lower level functions.
```

**4.** Given this array:

```js
let fruit = ["apple", "banana", "pineapple", "orange", "strawberry"];
```

What index is the pineapple's current position? How do you know?

<!-- enter you answer in the space below -->

```
fruit[2]
```

**5.** With these two objects:

```js
let you = { name: "You", hair: true, friends: [] };
let them = { name: "Them", hair: false, friends: [] };
```

how would you .push the `them` object into the `you` object's array of friends?

<!-- enter you answer in the space below -->

```
you.friends.push(them)

```

**6.** Give an example of a JavaScript `Conditional`:

<!-- enter you answer in the space below -->

```
if(true == true) {
  console.log("true")
}
```

**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "**\_\_**" space? What would you put here to increase `i` by one on every iteration?

```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```

<!-- enter you answer in the space below -->

```
The incrementor. i++
```

**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?

<!-- enter you answer in the space below -->

```
Document Object Model. The window object.
```

**9.** What are the `9` ECMAScript types as defined by MDN?

<!-- enter you answer in the space below -->

```
Boolean, Number, String, Undefined, Null, BigInt, Symbol, Object, Function
```

**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?

<!-- enter you answer in the space below -->

```
Parameters are place holders for values to be passed in. The values are the arguments.
```

**11.** What is the difference between a `primitive` value and a `reference` value?

<!-- enter you answer in the space below -->

```
When you access a primitive value you are working with the actual value in that variable. The reference is to its place in an object.
```
