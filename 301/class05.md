React Docs - Thinking in React

- What is the single responsibility principle and how does it apply to components?
The single-responsibility principle (SRP) is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.


- What does it mean to build a ‘static’ version of your application?
Static applications and websites render in the user's browser without the need for server side processing.


- Once you have a static application, what do you need to add?
Some site to deploy your website.

- What are the three questions you can ask to determine if something is state?
Is it in a {this.setState}?
Where is the contructor?
Is it being pushed into an object?


- How can you identify where state needs to live?
Higher-Order Functions
setState calls are batched, this lets you chain updates and ensure they build on top of each other instead of conflicting.


- What is a “higher-order function”?
A Higher-Order function is a function that receives a function as an argument or returns the function as output.

- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true

Line two is returning m equal to or greater then m less then n.


- Explain how either map or reduce operates, with regards to higher-order functions.
Map is the name of a higher-order function that applies a given function to each element of a collection, a list or set, returning the results in a collection of the same type. It is often called apply-to-all when considered in functional form.


Reference:
https://blog.bitsrc.io/understanding-higher-order-functions-in-javascript-75461803bad

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map#Polyfill

https://www.freecodecamp.org/news/higher-order-functions-in-javascript-d9101f9cf528/

https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK

