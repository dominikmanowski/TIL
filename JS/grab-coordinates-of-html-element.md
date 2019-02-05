# Grab X, Y, width and height of the HTML element

The method elem.getBoundingClientRect() returns window coordinates for elem as an `DOMRect` object with properties:

* top (y) – Y-coordinate for the top element edge,
* left (x) – X-coordinate for the left element edge,
* right – X-coordinate for the right element edge,
* bottom – Y-coordinate for the bottom element edge,
* height - height of the element in px,
* width - width of the element in px.

Window coordinates do not take the scrolled out part of the document into account, they are calculated from the window’s upper-left corner.

To include scrolled distance you have to add `window.scrollY` to `top` and `window.scrollX` to `left`.

