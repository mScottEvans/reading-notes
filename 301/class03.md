# Readings: Passing Functions as Props

- What does .map() return?
map() returns a map object, which is an iterator that yields items on demand.

- If I want to loop through an array and display each value in JSX, how do I do that in React?
attach the map() method to the array and pass a callback function that gets called for each iteration.

- Each list item needs a unique ____.
Key

- What is the purpose of a key?
 keys are used to give an identity to the elements in the lists.




- What is the spread operator?
It takes in an iterable and expands it into individual elements.

- List 4 things that the spread operator can do.
In the sum function definition below, the argument ...args means that we can call the function with any number of arguments. We can call the function with zero argument or multiple single arguments or with a spread operator applied to the number array .

1. We can use spread operator to merge two arrays, similar to the array concat function.

2. We can use spread operator to merge two objects, similar to the object.assign() function.

3. We can pass down props with the help of spread operator {...props}

4. When you want to make changes to at least one key/value pair.

- Give an example of using the spread operator to combine two arrays.
const arr1 = [1,2,3]
const arr2 = [4,5,6]
const arr3 = [arr1, arr2]

- Give an example of using the spread operator to add a new item to an array.
function sum(x, y, z) {
  return x + y + z;
}

const numbers = [1, 2, 3];

console.log(sum(...numbers));
// expected output: 6

console.log(sum.apply(null, numbers));
// expected output: 6


- Give an example of using the spread operator to combine two objects into one.

let person = {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356'
};


let job = {
    jobTitle: 'JavaScript Developer',
    location: 'USA'
};

let employee = {
    ...person,
    ...job
};

console.log(employee);

references: 
https://www.javascripttutorial.net/object/javascript-merge-objects/

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax
