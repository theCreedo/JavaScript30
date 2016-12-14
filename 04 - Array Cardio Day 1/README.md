# Goal:

Learn Array methods and conversions.

## Summary:

Worked on learning Array's filter, map, sort, and reduce, as well as how to shorten function syntax. You can either create an anonymous functions (function(...) {...} ) or arrow functions ( (...) => {...} ) for the input of the Array's methods. 

**NOTE:** Reduce is the only method that requires two parameters instead of one.

**NOTE:** For printing out filter or sort, instead of using console.log, we can use console.table in order to print out all the entries of the object returned into a very clean table.

We worked also with a wikipedia link, getting all link elements (<a>) and parsing out the text to get all Boulevards that had 'de' in their name. This was used using the '.includes' method, which returns a boolean value.

Additionally, we used ternary operators in order to reduce if/else statments to very short code. Ex. return (a == b) ? true : false;

## One Thing Learned:

In order to convert a NodeList into an array, you need to call 'Array.from(...)'. This will return you an Array, which allows you to use many more functions than just ForEach.