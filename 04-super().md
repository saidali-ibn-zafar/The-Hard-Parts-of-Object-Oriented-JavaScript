# super() 

- `super()` is a special keyword in JavaScript used inside classes to call the constructor of the parent class.


```js
class Animal {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }
}

class Dog extends Animal {
  constructor(name, age, breed) {
    super(name, age); // Call parent class's constructor with 'name' and 'age'
    this.breed = breed;
  }
}

const myDog = new Dog('Buddy', 5, 'Labrador');
console.log(myDog.name); // Output: Buddy
console.log(myDog.age); // Output: 5
console.log(myDog.breed); // Output: Labrador

```
