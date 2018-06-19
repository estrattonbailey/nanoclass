# nanoclass
84 byte classname utility.

# Usage
```javascript
import cx from 'nanoclass'

const cn = cx([
  'foo',
  true && 'bar',
  false && 'baz',
  0 ? 'qux' : 'quux'
])

console.log(cn) // => 'foo bar quux'
```

## License
MIT License © [Eric Bailey](https://estrattonbailey.com)
