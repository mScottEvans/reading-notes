# Readings: In memory storage

- What is a ‘call’?
The call() method is a predefined JavaScript method. It can be used to invoke (call) a method with an owner object as an argument (parameter). With call() , an object can use a method belonging to another object.

- How many ‘calls’ can happen at once?
JavaScript is the single-threaded programming language. This means that the JavaScript engine has only one call stack. Therefore, it only can do one thing at a time.

- What does LIFO mean?
last in, first out
It is a method for handling data structures where the first element is processed last and the last element is processed first.

- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.


- What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

- JavaScript error messages
Error: Permission denied to access property "x"
InternalError: too much recursion.
RangeError: argument is not a valid code point.
RangeError: invalid array length.
RangeError: invalid date.
RangeError: precision is out of range.
RangeError: radix must be an integer.

- What is a ‘reference error’?
A reference error is thrown when a code attempts to reference a non-existing variable.


- What is a ‘syntax error’?
An exception caused by the incorrect use of a pre-defined syntax. Syntax errors are detected while compiling or parsing source code. For example, if you leave off a closing brace ( } ) when defining a JavaScript function, you trigger a syntax error.

- What is a ‘range error’?
thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value. This can be encountered when: passing a value that is not one of the allowed string values to String. prototype

- What is a ‘tyep error’?
The TypeError object represents an error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type.

- What is a breakpoint?
JavaScript will stop executing, and let you examine JavaScript values.

- What does the word ‘debugger’ do in your code?
stops the execution of JavaScript, and calls (if available) the debugging function.



References: https://www.javascripttutorial.net/javascript-call-stack/#:~:text=JavaScript%20is%20the%20single%2Dthreaded,one%20thing%20at%20a%20time.

https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/#:~:text=What%20causes%20a%20stack%20overflow,before%20throwing%20a%20stack%20error.

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors

https://developer.mozilla.org/en-US/docs/Glossary/Syntax_error

https://www.w3schools.com/js/js_debugging.asp#:~:text=The%20debugger%20keyword%20stops%20the,debugger%20statement%20has%20no%20effect.

