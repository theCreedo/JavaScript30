# Goal:

This project will focus on keycodes pressed by the user, how the programmer can access/modify the object's data, as well as how functions can be formatted/called. (Keyevents, audio, and animation)

## Summary:

Each key on the keyboard has a given keycode number that is represented by it. You can see keycodes associated to the keys on keyboard [here](http://keycode.info). By setting the keycode value to objects in the window, you can access them collectively. By adding an EventListener to the window object (set to listen to 'keydown'), you can associate a function to be called every time that EventListener is triggered.

### Note:

You can set up an anonymous function or a regular function to be associated to your EventListener, just like in many other languages.

You can access the document object for any objects in the HTML document. By using the querySelector method, by specifying an object, you can get it saved into a user defined object. You will either access the given object, or get NULL. For this project, we use it in order to get the audio element, which is a file that contains the audio related to the key. We also use it in order to add a class to a CSS element.

Outside of the EventListener method, we need to remove any transforming changes to an element's class. Calling querySelectorAll, we can get all the elements associated to the key class. Using the forEach method on the key class, we can call the function removeTransition in order to remove any transition involving transform so that the animation for the key will not halt at the end animation, but will reset to it's original state.

### Note:

console.log() is useful for finding out the information that is stored within any elements or debugging.

## One Thing Learned:

One of the biggest things I learned during this project (which would've fixed a lot of errors that I had previously with audio), was that I could set the value of the audio's currentTime to 0. This will instantly set the audio's playing time back at the beginning, preventing audio from overlapping, and allowing repetitive playing of an audio file.


