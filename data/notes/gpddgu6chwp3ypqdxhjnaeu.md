
## Selecting

[[js.dom.querying]]

## Create a dom node

[[js.dom.createElement]]

## Working with Classes

[[js.dom.classList]]

## Working with attributes

### Custom data attributes

- when setting custom attributes use `data-*`
- set a data attribute value:
- The in operator can check if a given attribute exists: `'keyname' in element.dataset`
- To remove an attribute, you can use the delete operator: `delete element.dataset.keyname`

```html
<p data-user="Adam Bragg">Adam</p>
```

```js
const element = document.querySelector('p');
element.dataset.user; // Adam Bragg
```

```js
element.dataset.food = 'pizza'; // create new attribute and set data attribute
// <p data-user="Adam Bragg" data-food="pizza">Adam</p>
```

### Working with attributes

-

## Traversing through the DOM
