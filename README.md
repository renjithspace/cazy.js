# Cazy.js
Collecting some crazy JavaScript codes

#### String Immutability
String literal cannot be changed
```js
var name = 'Bob'
name[0] = 'J'
console.log(name[0]) // Expected J, But B
```

#### Template Literals
```js
console.log(`Hello world`) // Hello world
console.log `Hello world` // ['Hello world']
```
