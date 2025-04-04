# GitHub Actions Example

**math.js**
```js
function add(a, b) {
  return a + b;
}

module.exports = { add };
```

**math.test.js**
```js
const { add } = require('./math');

test('adds 1 + 2 to equal 3', () => {
  expect(add(1, 2)).toBe(3);
});
```

