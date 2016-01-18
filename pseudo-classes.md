# Pseudo-Classes


You've already had a some practice with pseudo-classes (perhaps without being fully aware of it), but check out this basic [refresher](http://www.htmldog.com/guides/css/intermediate/pseudoclasses/) on what they are and how they work. You might also want to check out a few other use cases for them.

Codrops has an awesome [reference](http://tympanus.net/codrops/css_reference/#section_css-pseudo-class) list if you want to check that out as well.

Note: You do not need to know how to do every example from these resources, per se. The purpose of this particular lesson is to reinforce a basic familiarity with the many pseudo classes available to you -- it will come in handy in the coming days.

#Summary

ia Treehouse:

Think of a pseudo-class as a keyword we add to a selector to style a special state of an element.

The :link pseudo-class targets links that have not been visited by the user:
```
a:link {
  color: orange;
}```
The :visited pseudo-class targets links that have been visited –– or clicked –– by the user:
```
a:visited {
  color: lightblue;
}```
The :hover pseudo-class targets an element when a user hovers over it:
```
a:hover {
  color: forestgreen;
}```
The :active pseudo-class gets applied when an element is in an active state:
```
a:active {
  color: lightcoral;
}```
The :focus pseudo-class is only applied to interactive elements like links, buttons and form elements. The styles are applied as soon as the element receives focus:
```
a:focus {
  color: white;
  background-color: orange;
}```
