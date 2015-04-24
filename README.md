# wats1020-dom-basics
In this assignment students explore the native tools provided in Javascript to
navigate and affect the DOM. To practice these techniques, we will createa
Fortune Cookie Generator page that will show you a saying like you might find
in a fortune cookie.

Feel free to have fun with this, and there are lots of ways to stretch in this
assignment. If done right, this could be a fun portfolio piece.

## Basic Requirements
To complete the base level of this assignment, you must fulfill the following
requirements:

* Add an `onclick` attribute to the "Make My Fortune!" button so it executes the `generateFortuneCookie()` function when it is clicked.
* In the `fortune-cookie-generator.js` create the logic to display a fortune:
    * Select the `#fortune-cookie-text` element.
    * Append the current text in the `#fortune-cookie-text` element as a list item (`li`) within the `#previous-fortunes-container` list.
    * Select a random fortune cookie saying from the `fortunesList` Array.
    * Replace the `innerText` of the `#fortune-cookie-text` element with the data you selected from `fortunesList`.
* Make sure a fortune is generated each time the user clicks the button.

## Stretch Goals
This assignment allows for a large number of possible stretch goals. You are encouraged to stretch in additional ways if you can think of fun/interesting things to try. Here are some ideas:

* It's currently possible to randomly select the same fortune twice in a row. Can you think of a way to check if the new saying is the same as the previous saying and prevent it from showing up? Can you think of a way to keep track of all the sayings that have been used and prevent a saying from being repeated until the entire list has been exhausted?
* This page is begging for some cute visuals. Use CSS to style the elements in the HTML. Feel free to add or rearrange HTML elements to fit your vision.
* You could show additional statistics on the page, such as how many fortunes have been generated. Add those in an appealing way.
* What if people want to generate fortunes for their whole table? Why not allow somebody to generate multiple fortunes at the same time? How would you change the code and HTML to support that?
