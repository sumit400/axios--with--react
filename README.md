# axios--with--react
This is a basic axios how to use in React. This help us to use API in react we can use GET, POST, PUT, DELETE. This is a best way to use API
Introduction to Axios: Axios, which is a popular library is mainly used to send asynchronous HTTP requests to REST endpoints. This library is very useful to perform CRUD operations.
Here are five reasons why you should use Axios as your client to make HTTP requests:

It has good defaults to work with JSON data. Unlike alternatives such as the Fetch API, you often don't need to set your headers. Or perform tedious tasks like converting your request body to a JSON string.
Axios has function names that match any HTTP methods. To perform a GET request, you use the .get() method.
Axios does more with less code. Unlike the Fetch API, you only need one .then() callback to access your requested JSON data.
Axios has better error handling. Axios throws 400 and 500 range errors for you. Unlike the Fetch API, where you have to check the status code and throw the error yourself.
Axios can be used on the server as well as the client. If you are writing a Node.js application, be aware that Axios can also be used in an environment separate from the browser.

This popular library is used to communicate with the backend. Axios supports the Promise API, native to JS ES6.
Using Axios we make API requests in our application. Once the request is made we get the data in Return, and then we use this data in our project.


Step 1: Below is the command to create React app in your project…

npx create-react-app new_files
Step 2: Enter in the directory created in the first step.

cd new_files
Step 3: Install Axios library using the command given below…

npm install axios
Step 4: Once this has been done, you can start the server using the command given below..

npm start
After Axios installation, you can import this library into your file and use it to make an HTTP request.
