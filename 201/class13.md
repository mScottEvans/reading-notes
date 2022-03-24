## “The Past, Present, and Future of Local Storage for Web Applications”

## HTML5 specification introduces the localStorage as a way to store data with no expiration date in the web browsers.

In other words, the data stored in the browsers will persist even after you close the browser windows.

The data stored in the localStorage is bound to an origin. It means that the localStorage is unique per protocol://host:port.

## You can access the localStorage via the property of the window object:

window.localStorage
Code language: JavaScript (javascript)
Since the localStorage is an instance of the Storage type, you can invoke the methods of the Storage type to manage data.

When you type the following code in the Console:

window.localStorage
Code language: JavaScript (javascript)
… you’lll see the following object:

Storage {length: 0}



### References: https://www.javascripttutorial.net/web-apis/javascript-localstorage/