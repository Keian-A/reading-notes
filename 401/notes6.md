# Read-06

## Notes on Authentication

- Explain what a “Singleton” is (in Computer Science terms)
  - This is when a class is restricted to only a single instantiation
- Explain how the Singleton pattern can be used with Node modules, specifically with classes
  - By exporting a module of a single class, when you `require` the module, this is used as a single instantiation of the class
- If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?
  - If I was taked with this, I would construct a function-type environment where one could use callback-like functions to call the next function (or route) in the list

- Router Middleware
  - These are functions that are used when specific conditions are met, or if used within an `app.use()`, will be activated through every request sent to the server
- Dynamic Module Loading
  - Loading modules dependently depending on the environment
- Singleton Pattern
  - This is the process of instantiating only once instance of a class, usually done through a module exports, then required into the module used
- CRUD -> REST Method Matches
  - This is an acronym that stands for Create, Read, Update, and Delete. These are the functions that can be done with routes and the interactions the user can have with a database
- Mock Testing
  - This is the method of creating tests to test written code before production, to see if what the client is recieving is the intended information