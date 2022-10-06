# Day 5

## Concepts

- Classes

## Classes

- JavaScript is an object oriented programming language. 
- Everything in JavScript is an object, with its properties and methods. 
- We create class to create an object. [A Class is like an object constructor, or a "blueprint" for creating objects.]

```
// syntax
class ClassName {
    //  code goes here
}
```

## Class Instantiation 

- Creating an object from a class

```
class Person {
  // code goes here
}
const person = new Person()
console.log(person)
```

## Class Constructor

- The constructor is a builtin function which allows as to create a blueprint for our object.

```
class Person {
  // constructor of Person class
  constructor(firstName, lastName) {
    console.log(this) // Check the output from here
    this.firstName = firstName
    this.lastName = lastName
  }
}

const person = new Person()
console.log(person)
```

