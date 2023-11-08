
- Array.from() method is a static method in JavaScript
- it creates a new array instance from an iterable or array-like object
- The iterable or array-like object can be any object that has a length property and can be iterated over using a for…of loop or other iterable method.
- The method returns a **shallow copy of the original object**
- **any changes made to the original object will not affect the new array instance created by﻿Array.from()**

```js
// Create an array based on a property of DOM Elements

const images = document.querySelectorAll('img');
// returns a NodeList

const sources = Array.from(images, (image) => image.src);

const insecureSources = sources.filter((link) => link.startsWith('http://'));
```
