# Example

```shell
$ npm install sensitive-word --save
```

```javascript
const {sensitiveWords} = require('sensitive-word')
// ES2015 modules
import {sensitiveWords} from 'sensitiveWords'

const filtered =
  sensitiveWords(
    'The new apple mackbook pro will have a touchbar',
    ['pro','touchbar']
  );

console.log(filtered);
// The new apple mackbook *** will have a ***
```