# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
abstraction, encapsulation, inheritance and polymorphism

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
return staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
encapsulation is when you group together "like" code or code that does similar things.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
single responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
a 'class' is like a model/blueprint of what any given instance of a class should look like or the data it should contain.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
a proxy object is just that. Its a copy of an object that is used to create layers that way we can seperate the user from accessing our code.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
the MVC pattern is used so that we can encapsulate our code into smaller files, accessing them through imports and exports. it also makes it easier to add or delete objects from our html.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
the controller recieves user input and sends it to the service
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
service pulls from the appstate and the model all of the information it needs to create instances of the classes we create.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
the model is the blueprint that all other instances will follow in order to create new class instances.
```

