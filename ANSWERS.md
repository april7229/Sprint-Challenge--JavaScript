# Your responses to the short answer questions should be laid out here using Mark Down.
1. Describe the biggest difference between `.forEach` & `.map`.
.forEach is one of the most powerful functions .It does one thing really really well, iterate over a list of data and in turn pass back an item and index to us for use..forEach doesn’t return us anything like .map does. 
2. What is the difference between a function and a method?
Functions in JavaScript are first class citizens”JavaScript methods are the actions that can be performed on objects. A JavaScript method is a property containing a function definition. Property. Value. firstName
3. What is closure?
A closure is an inner function that has access to the outer (enclosing) function's variables—scope chain. The closure has three scope chains: it has access to its own scope (variables defined between its curly brackets), it has access to the outer function's variables, and it has access to the global variables.
4. Describe the four rules of the 'this' keyword.
As a constructor While the default for a constructor is to return the object referenced by this, it can instead return some other object (if the return value isn't an object, then the this object is returned).As an object method When a function is called as a method of an object, its this is set to the object the method is called on.Arrow functions n arrow functions, this retains the value of the enclosing lexical context's this. In global code, it will be set to the global object:The bind methodECMAScript 5 introduced Function.prototype.bind. Calling f.bind(someObject) creates a new function with the same body and scope as f, but where this occurs in the original function, in the new function it is permanently bound to the first argument of bind, regardless of how the function is being used.
5. Why do we need super() in an extended class?
When used in a constructor, the super keyword appears alone and must be used before the this keyword is used. The super keyword can also be used to call functions on a parent object.
