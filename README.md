# sass-media-width
Create a width-based media query using a SASS mixin.

## To-do:
* How should global breakpoints list be referenced/passed in?
* Allow any unit type, not just px.
* Switch to more general sass media query and allow other queries like height?
* Change to simpler arguments syntax:
	* `media-width(< medium)`
	* `media-width((>= medium), (< large))`