---
id: 7s6nvh1ynr6yzux6k37yhn9
title: classList
desc: ''
updated: 1698355594349
created: 1698355156321
---

`Element.classList` is a property that returns a live collection of the classes on an element.

There are methods to add, remove, replace, toggle and check for the classes on an element;

```js
const element = document.createElement('div');

element.classList.add('class'); // add a class of 'class'
element.classList.add('another-class'); // add class of 'another-class'

element.classList.remove('class'); // remove class of 'class'
element.classList.replace('another-class', 'new-class'); // replace class of 'another-class' with 'new-class'
element.classList.toggle('class'); // toggle class of 'class'
element.classList.contains('new-class'); // check if element has class of 'new-class'

// create a toggle function;
function toggleClass(element, className) {
  if (!element || !className) return;
  element.classList.toggle(className);
}
```
