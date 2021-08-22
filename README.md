# deep-merge-node-2


step 1 : npm install

### Usage(example)

```
const deepMerge = require('node-deep-merge');

const object = { a: [{ b: 2 }, { d: 4 }] };
const other = { a: [{ c: 3 }, { e: 5 }] };

console.log(deepMerge.merge(object,other))

