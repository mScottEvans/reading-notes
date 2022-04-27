Readings: CRUD

- In your own words, describe what each group of status code represents:

100’s = Informational responses 
200’s = Successful responses 
300’s = Redirection messages 
400’s = Client error responses 
500’s = Server error responses  

- What is a status code 202?
indicates that the request has been accepted for processing, but the processing has not been completed

- What is a status code 308?
the resource requested has been definitively moved to the URL given by the Location headers.

- What code would you use if an update didn’t return data to a client? 
500s

- What code would you use if a resource used to exist but no longer does?
404

- What is the ‘Forbidden’ status code?
the server understands the request but refuses to authorize it.


- Why do we need to pull our MongoDB database string out of our server and put it into our .env?
so they can work through the web.

- What is middleware?
helps you with logging, error reporting, making asynchronous requests, and a whole lot more.

- What does app.use(express.json()) do?
parses incoming JSON requests and puts the parsed data in req. body
parses incoming JSON requests and puts the parsed data in req. body .

- What does the /:id mean in a route?
string.

- What is the difference between PUT and PATCH?
PUT is a method of modifying resource where the client sends data that updates the entire resource . PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.

- How do you make a default value in a schema?
const schema = new Schema({
  title: String,
  date: {
    type: Date,
    // `Date.now()` returns the current unix timestamp as a number
    default: Date.now
  }
});

- What does a 500 error status code mean?
the server encountered an unexpected condition that prevented it from fulfilling the request.

- What is the difference between a status 200 and a status 201?
 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created

References: https://stackoverflow.com/questions/11746894/what-is-the-proper-rest-response-code-for-a-valid-request-but-an-empty-data
https://mongoosejs.com/docs/defaults.html

https://aloneonahill.com/blog/http-status-codes#:~:text=The%20200%20status%20code%20is,understood%20and%20is%20being%20processed.&text=A%20201%20status%20code%20indicates,for%20example%20a%20new%20page).

https://www.geeksforgeeks.org/difference-between-put-and-patch-request/#:~:text=PUT%20is%20a%20method%20of%20modifying%20resource%20where%20the%20client,without%20modifying%20the%20entire%20data.
