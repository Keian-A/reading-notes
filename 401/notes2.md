# Read-02

1. Describe (in plain English) what Array.map() does
  - .map() is a method on an array that iterates through each item in an array and returns a new array with whatever edits may have been done to each item through the callback function.
2. Describe (in plain English) what Array.reduce() does
  - .reduce() is a method on an array that uses a callback function to edit a value in some way for each value in the array and returns the value at the end of the iterations.
3. Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
- With normal Promise .then() syntax
- Again with async / await syntax

``` javascript
request
  .get('/search')
  .then(res => {
    // res.body, res.headers, res.status
  })
  .catch(err => {
    // err.message, err.response
  });

try {
  const res = await request
    .get('http+unix://%2Fabsolute%2Fpath%2Fto%2Funix.sock/search');
  // res.body, res.headers, res.status
} catch(err) {
  // err.message, err.response
}
// Examples taken from https://visionmedia.github.io/superagent/
```

4. Explain promises as though you were mentoring a Code 301 level student.
  - In order for the client (the person who is interacting with a website) to communicate with a server (the place that houses all the data) they must send WRRC (web request response cycle) requests to the server to ask for information. This process of asking the server for information is called a promise.
5. Are all callback functions considered to be Asynchronous? Why or Why Not?
  - No, source from [here](https://stackoverflow.com/questions/19083357/are-all-javascript-callbacks-asynchronous-if-not-how-do-i-know-which-are). Apparently this needs to be checked from the documentation fo the specific callback function you are using.

[<-- Back](ToC.md)