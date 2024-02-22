# `new` and `this` keywords

- The `new` keyword is introduced as a feature that automates certain tasks when creating objects in JavaScript. It automates the creation of the object, returning the object automatically. 
- When a constructor function is called with the `new` keyword, a new object is created. Inside the constructor function, the `this` keyword refers to the newly created object. This allows you to access and modify properties and methods of the object being created within the constructor function.

  ```js
  function Person(name, age) {
    this.name = name; // 'this' refers to the newly created object
    this.age = age;   // 'this' refers to the newly created object
  }

  var person1 = new Person("John", 30);
  console.log(person1.name); // Output: John
  console.log(person1.age);  // Output: 30
  ```
