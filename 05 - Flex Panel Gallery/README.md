# Goal:

Learn how to work with flex. Combination of adding CSS attributes for flex and transforming characteristics with flex.

## Summary:

A lot of CSS attributes have to be added to this websites in order to allow for much of the formatting (flex, justify-content, align-content, display, flex-direction.)

Classes can be added with operations (>, <, etc...) in order to indicate the children within a given element to change a certain format. (Ex. .panel > *:last-child). These transformations are triggered based on the class contained within an element. When transformations happen, the time it takes for transformations to take place change based on transition set in classes.

**NOTE:** Keeping flex at 1 will ensure that all the parts that contain that flex will only take up 1x of the given section. Changing number changes the ratio that is taken up (5 => 5 times).

## One Thing Learned:

The transitionend propertyname for Safari ('flex') is different compared to Chrome or FireFox ('flex-grow'). In order to accomadate both versions when taking note of the transitionend's propertyname, use 'includes('flex')' to cover both cases. 

