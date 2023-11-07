
- NodeLists are a static collection, example: If you add a `<li>` element to a list in the DOM, the list in NodeList will not change.
- A NodeList is not an array but can be looped over with forEach()
- A NodeList can be converted to an array with Array.from see: [[js.array.from]]
- A NodeList can be converted to an array with the spread operator `[...nodeList]`
- `document.querySelectorAll()` and `childNodes()` return a NodeList

see: [[js.dom.querying]] for more info on `document.querySelectorAll()`
