# Goal:

Learn how to manipulate CSS aspects through JavaScript.

## Summary:

CSS elements can be edited through getting the class elements with querySelector and changing the style attribute of the class element. For us, we changed the style.transform attribute, calling the rotate method and changing each time-hand type with their respective degrees (hour, min, second). We made sure that this function change updated the hand's position would only be called at given interval times (every 1 sec). We set the transform origin to 100% so that the hand would rotate based on the x axis of the image. Additionally, we changed the transition for all hands to be 0.05 seconds so they would have a mini buffer time. Furthermore, we changeed the transition-timing-function based on the cubic-bezier function (changing some values through a simple interface.) so that the change would have some repetitive backwards/forwards motion to mimic the clock hands jittery movement.

**NOTE:** There is a small choke for the program when the seconds reach 0. At that point, the second (and potentially minute/hour) hand causes a very abrupt stutter in the UI update. Can be fixed with some simple if/else statements 


## One Thing Learned:

JavaScript scripts are not to difficult to make, but creating the initial interface and design takes quite some time. Fortunately these proejcts come with sample code, making it easy just to focus on the back-end code.

