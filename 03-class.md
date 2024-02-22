# Class (`syntactic sugar`)

- Classes are a template for creating objects.

- A JavaScript class is `not` an object. It is a `template` for JavaScript objects.

- - - - 

- When you have a class, you can use the class to create objects:


```js
class Car {
  constructor(name, year) {
    this.name = name;
    this.year = year;
  }
}
```

```js
const myCar1 = new Car("Ford", 2014);
const myCar2 = new Car("Audi", 2019);
```

- - - - 

- Overall syntax:
```js
class ClassName {
  constructor() { ... }
  method_1() { ... }
  method_2() { ... }
  method_3() { ... }
}
```
