# Goal:

Learn how to interact with endpoint data, work with regex, and insert additional html code.

## Summary:

To make a request for data, you can use fetch(...) with the http url of the data. You can add a then(...) in order to add a function to reformat the data. In our code, we fetch the json data, then reformat it into json, and then finally we take the data, spread it out '...', and push it into a const array where our data will be stored.

Once again, we come back to our eventListeners. After querySelector'ing the search element, we add eventListners with methods in order to assert whether a 'change' or a 'keyup' occurs and call the displayMatches() function. Our displayMatches function will call findMatches(..., ...), which will find all cities/states that are related to the keyword searched (through Regex object) and return an array of those Objects.

Using the .map(...) method, we can change the innerHTML code of the suggestion element in order to show which cities/states are related to the search keyword. Adding a <span> with class of 'h1' allowed for highlighting the parts of the word that were related. I believe that innerHTML initially (first time) doesn't contain anything (unless initially set), so the html of suggestions just gets replaced each time a change in keyword is made.

## One Thing Learned:

With JavaScript, you can inject additional html code through these `` marks. Setting that code to the given innerHTML of any element (or possibly other areas) will change up the code to contain those additional characteristics within the code. This is good if you want to reproduce many elements that show data, change up the view of the interface, or do other flashy html additions.