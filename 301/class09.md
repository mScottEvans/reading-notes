#  Readings: Functional Programming





# Functional Programming Concepts

- What is functional programming?
In computer science, functional programming is a programming paradigm where programs are constructed by applying and composing functions. It is a declarative programming paradigm in which function definitions are trees of expressions that map values to other values, rather than a sequence of imperative statements which update the running state of the program.

- What is a pure function and how do we know if something is a pure function?
A pure function is a function that has the following properties: the function return values are identical for identical arguments (no variation with local static variables, non-local variables, mutable reference arguments or input streams)

- What are the benefits of a pure function?
All relevant inputs and dependencies are provided as parameters, so no effects are observed that alter variables outside of the set of inputs. This means that we can quickly understand a function and its dependencies, just by reading the function's declaration.

- What is immutability?
an immutable object (unchangeable object) is an object whose state cannot be modified after it is created. This is in contrast to a mutable object (changeable object), which can be modified after it is created.

- What is Referential transparency?
referential transparency is generally defined as the fact that an expression, in a program, may be replaced by its value (or anything having the same value) without changing the result of the program.


## Node JS Tutorial for Beginners #6 - Modules and require()

- What is a module?
A module in JavaScript is just a file containing related code. In JavaScript, we use the import and export keywords to share and receive functionalities respectively across different modules.

- What does the word ‘require’ do?
require() is used to consume modules. It allows you to include modules in your app. You can add built-in core Node. js modules, community-based modules (node_modules), and local modules too.

- How do we bring another module into the file the we are working in?
In Node.js, any file that consists of JavaScript code in a file ending with .js is a module. A module can contain definitions of functions, classes, objects, or variables that can be referenced or used in another Javascript file.

- What do we have to do to make a module available?
The first thing you do to get access to module features is export them. This is done using the export statement. You can export functions, var , let , const , and — as we'll see later — classes. They need to be top-level items; you can't use export inside a function.

References: https://betterprogramming.pub/what-is-a-pure-function-3b4af9352f6f
https://alvinalexander.com/scala/fp-book/benefits-of-pure-functions/
https://www.tiny.cloud/blog/mutable-vs-immutable-javascript/
https://www.sitepoint.com/what-is-referential-transparency/
https://www.freecodecamp.org/news/javascript-modules-explained-with-examples/#:~:text=A%20module%20in%20JavaScript%20is,object%20accessible%20to%20other%20modules.

