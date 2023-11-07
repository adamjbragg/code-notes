---
id: pusx7u7k32x2g7sevzjadb9
title: insertAdjacentElement
desc: ''
updated: 1699306799052
created: 1699174638995
---

`Element.insertAdjacentElement()` is a method that inserts an element at a defined position relative to the element invoked from.

`insertAdjacentElement(position, element)`

- there are four positions
  -- `beforebegin`: before the `targetElement`
  -- `afterbegin`: inside the `targetElement`
  -- `beforeend`: just inside the `targetElement`
  -- `afterend`: after the `targetElement`

```js
const targetEl = documentQuerySelector('.someClass');

const myEl = document.createElement('p');
myEl.innerText = 'This is my element';

targetEl.insertAdjacentElement('afterbegin', myEl);
```
