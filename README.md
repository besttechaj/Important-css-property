# Important-css-property
Examples based on css property's topics


****************** POSITIONING OF ELEMENT ****************************************


 By default browser always gives us static position , if you want to change the element position then use css margin property 

 position:relative ... you can position  your element anywhere including over the other element 


position:absolute -> this completely removes the element from the document flow[consecutive displaying of the element] .and every others element renders as they were before and they pretend like absolute element was not exist in the document flow.

-The element is positioned relative to its first positioned (not static) ancestor element

IMPORTANT NOTES:
So, there are several types of positioning: static, relative, absolute, fixed, sticky, initial and inherit. First of all, let’s explain what all of these types mean.

Static - this is the default value, all elements are in order as they appear in the document.
Relative - the element is positioned relative to its normal position.
Absolute - the element is positioned absolutely to its first positioned parent.
Fixed - the element is positioned related to the browser window and ignores its parent element.(used in scrolling)
Sticky - the element is positioned based on the user’s scroll position.combination of both absolute and relative
