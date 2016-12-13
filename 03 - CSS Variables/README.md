# Goal:

Learn how to update CSS variables through Javascript.

## Summary:

Any element that geta set to a certain CSS variable will be updated by the value of that CSS variable if it gets updated through JavaScript. There is a root selector that can be set certain values based on different CSS declarations. We use querySelectorAll in order to access the Node List of all .controls class elements. We have eventListeners over the elements through keywords 'change' (when a slider or color changer is moved and changed the moment after releasing hold of color/position selector) and 'mousemove' (when a slider or color changer changes as it is move, without releasing hold of color/position selector).

**NOTE:** A Node List contains less informational data than an Array data structure. When you call querySelectorAll, unless you convert it, you get a Node list.

We have a div class in our HTML that contains the 'controls' to edit the spacing, blur, and color of the website. Data can be saved within 'input' containers (data such as the value, type, and name). These 'input' values can be assigned to different elements in the document so that whenever that value changes, the CSS element associated to that variable will change also. 

## One Thing Learned:

For CSS variables, you must add an additional '--' before the variable name in order for the value held within the variable to be stored, edited, or assigned.

