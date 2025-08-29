

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
ans:
getElementById → one element by ID

getElementsByClassName → multiple by class (HTMLCollection)

querySelector → first match by CSS selector

querySelectorAll → all matches (NodeList)




2. How do you **create and insert a new element into the DOM**?
ans:
document.createElement() and then attach it.



3. What is **Event Bubbling** and how does it work?
ans:
When an event (like a click) happens on an element, it first runs on the target element, then “bubbles up” to its parent, then grandparent, all the way up to document.




4. What is **Event Delegation** in JavaScript? Why is it useful?
ans:
A technique where you attach one event listener on a parent element instead of adding listeners to many child elements.
It works because of event bubbling.
Better performance (less memory usage).
Handles dynamically added elements automatically.



5. What is the difference between **preventDefault() and stopPropagation()** methods?
ans:
preventDefault() → Stops default browser action (like form submit, link navigation).

stopPropagation() → Stops event bubbling to parents. 


