
In modern JS we use `document.querySelector()` and `document.querySelectorall()` to select elements in the dom.

## `document.querySelector()`

Returns the **first** element that matches the given selector(s).

```js
const elByClass = document.querySelector('.class');
const elById = document.querySelector('#id');
const elByTag = document.querySelector('tag'); //('h1')
const elByAttr = document.querySelector('[attr]'); //('[data-attr]')
```

## `document.querySelectorAll()`

Returns a **node list** of all elements that match the given selector(s).

```js
const elByClass = document.querySelectorAll('.class');
const elById = document.querySelectorAll('#id');
const elByTag = document.querySelectorAll('tag'); //('h1')
const elByAttr = document.querySelectorAll('[attr]'); //('[data-attr]')
```

## Accessing the matches from `document.querySelectorAll()`

Because `document.querySelectorAll()` returns a nodeList we can access the matches with a forEach loop.

```js
const elements = document.querySelectorAll('.class');

// loop over the element with forEach()
element.forEach((el) => {
  console.log(el); // do something with the element
});
```

NodeLists can be converted to Arrays, see: [[js.dom.nodeList]] for more information.
