# jQuery

# these from my sammary while jquery course 



# jQuery

library from www.jquery.com, or, as an alternative, you can include it from a CDN (Content Delivery Network), like Google or Microsoft.

### you add it  to your html
```
<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
        <script src="https://code.jquery.com/jquery-3.1.1.js"></script>
    </head>
    <body>
    </body>
</html>
HTML


```

### jQuery methods

* The html() method is used to change the HTML content of an element.
* The text() method is used to show only the text content, without the HTML markup
* The hide() method is used to hide the HTML content of an element.
* The show() method is used to hide the HTML content of an element.
* The removeAttr() method is used to remove attributes from HTML elements.
* The val() method, which allows us to get and set the values of form fields, such as textboxes, dropdowns, and similar inputs.
* The parent() method returns the direct parent element of the selected element.
* The parents() To get all ancestors of the selected element you can use the parents() method.
* The eq() method can be used to select a specific element from multiple selected elements.
* the remove() We remove selected elements from the DOM using the remove() method.
* The empty() method is used to remove the child elements of the selected element(s).
* The on() method is used to attach an event to the selected element <!-- $( "p" ).on( "click dblclick", function() { alert("clicked"); }) -->
* the off() You can remove event handlers using the off() method.
* the trigger() We can also trigger events programmatically using the trigger() method
* the fadeInfadeOut methods, which fade an element in and out of visibility.
* The slideUp() and slideDown() methods are used to create a sliding effect on elements.
* The animate() method lets you animate to a set value, or to a value relative to the current value.  / all property names must be camel-cased when used with the animate() method
* The stop() method To stop an animation before it is finished, jQuery provides the stop() method.



#### Summary
The following jQuery methods are available to get and set content and attributes of selected HTML elements:
text() sets or returns the text content of selected elements.
html() sets or returns the content of selected elements (including HTML markup).
val() sets or returns the value of form fields.
attr() sets or returns the value of attributes.
removeAttr() removes the specified attribute.



jQuery has methods that are used to add new content to a selected element without deleting the existing content:

* append() inserts content at the end of the selected elements.
* prepend() inserts content at the beginning of the selected elements.
* after() inserts content after the selected elements.
* before() inserts content before the selected elements.
* 




## Common Events


The following are the most commonly used events:
Mouse Events:

click occurs when an element is clicked.
dblclick occurs when an element is double-clicked.
mouseenter occurs when the mouse pointer is over (enters) the selected element.
mouseleave occurs when the mouse pointer leaves the selected element.
mouseover occurs when the mouse pointer is over the selected element.

Keyboard Events:

keydown occurs when a keyboard key is pressed down.
keyup occurs when a keyboard key is released.

Form Events:
submit occurs when a form is submitted.
change occurs when the value of an element has been changed.
focus occurs when an element gets focus.
blur occurs when an element loses focus.

Document Events:
ready occurs when the DOM has been loaded.
resize occurs when the browser window changes size.
scroll occurs when the user scrolls in the specified element.

As an example, let's change the content of a div when the user types in an input field. To do that, we need to handle the keydown event, which occurs when a key on the keyboard is pressed:
HTML:









## The Event Object


Every event handling function can receive an event object, which contains properties and methods related to the event:
pageX, pageY the mouse position (X & Y coordinates) at the time the event occurred, relative to the top left of the page.
type the type of the event (e.g. "click").
which the button or key that was pressed.
data any data that was passed in when the event was bound.
target the DOM element that initiated the event.
preventDefault() prevent the default action of the event (e.g., following a link).
stopPropagation() Stop the event from bubbling up to other elements.




 ### Why pair program?

 1. Greater efficiency
 2. Engaged collaboration
 3. Learning from fellow students
 4. Social skills
 5. Work environment readiness

