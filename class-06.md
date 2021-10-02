# JS objects, DOM

## Understanding The Problem Domain Is The Hardest Part Of Programming

* **The Problem Domain**  - undersatanding the problem domain and what issue you are trying to solve is the lynch pin that will make or break any project. Having a proper understanding of what the issue is and what is needing to be changed/fixed is the only way to be successful. Dont get focused on coding and skipping over the human interaction. Finding the problem and understanding it or breaking it down to smaller parts.

## What’s the Difference Between Primitive Values and Object References in JavaScript?

* when a primitive value is assigned to a variable the variable ia set as the value and not a refernce.

* variable store objects not as a value but as a reference point to the container (object).

* obejects are mutable, this means they can be changed. Values cannot be changed unless they are wiped and rewriiten/reassigned.

* it is recommended that you use `===` over `==` whenever possible.

JS supports 8 data types symbol, string, number, null, booleans,undefined,BigInt, and Objects. the first 7 are primitice values.

## Ch. 3 Object Literals / JS & JQUERY

* Objects list a group of variables together. Variables in an object are called Properties. Functions inside of Object are called Methods. in objects the name of variables and functions is called the key and he assigned value is called value.

    - `const hotel = {name:Oak};`   

## Ch.5 Document Object Model / JS & JQUERY  

* DOM is a tree layout of an application and will have all gthe parts listed out and divided in branches. 
 
    - `getElementById()` - uses the id tag to finad all elements with that id

    - `querySelector()` -  uses CSS selector and returns the first element that matches.

    - `getElementByClassName()` - selects all elements with a certain class assigned

    - `getElementByTagName()` - selects all elements with the tag selected.

    - `querySelectorAll()` - uses a CSS selector to select all elements that match.

    - `parentNode` - selects the parent of the current node.

    - `nextsibling/previoussibling` - selects the next or the previous sibling

    - `lastChild/firstChild` - selects the last or first child in the current element.

Sonmez, John. "Understanding The Problem Domain Is The Hardest Part Of Programming" Simple Programmer, 15 Jul 2013, https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming

Geelhoed, Chris. "What’s the Difference Between Primitive Values and Object References in JavaScript?" Better Programming, 16 Jan 2020, https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b

Duckett, J (2011). JAVASCRIPT & JQUERY Interactive front-end web development , 100-105,183-242

All definitions and information came from above listed publication(s).

[<===Back>](README.md)