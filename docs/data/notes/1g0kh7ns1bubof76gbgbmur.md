
`node.textContent` returns all the contents of a node including text, but also script and style tags, hidden divs and white space.

```html
<h2>Hello World</h2>
```

```js
const h2 = document.querySelector('h2');
h2.textContent; // Hello World
```

- **Warning:** Setting textContent on a node removes all of the node's children and replaces them with a single text node with the given string value.

### Differences from `HTMLElement.innerText`

- `textContent` returns every element with in a node, `innerText` is aware of styling and won't return hidden elements.
- `innerText` triggers a reflow, `textContent` does not.

see: [[js.dom.innerText]]
