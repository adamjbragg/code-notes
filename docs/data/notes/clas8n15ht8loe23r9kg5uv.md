
HTMLElement.innerText is a property that returns the human readable text from a node and its descendants.

### Differences from `node.textContent`

- `innerText` is aware of styling and won't return hidden elements.
- `innerText` triggers a reflow, `textContent` does not.
- `textContent` returns every element with in a node including script and style tags, hidden divs and white space.
