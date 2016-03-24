Subschema Server Utils
======================
This project provides validateFactory for easy consumption on the server
side.   When the server only needs to validate data against a schema
it may or may not need to be 

## Installation
```sh
  npm i subschema-server-utils --save
 
```

## Usage:
validateFactory returns a function, takes a schema and a loader.
The returned function takes a value or valueManager and returns a promise.
If no errors, the promise returns null, other wise an object containing
the errors is returned

see [tests](./test/validateFactory-test.js) for more information on usage.

