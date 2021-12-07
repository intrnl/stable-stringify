Stable JSON stringify

```js
import { stableStringify } from '@intrnl/stable-stringify';

stableStringify({ c: 1, b: [7, { y: 2, z: 3, x: 1 }, 1], a: 3 });
// -> '{"a":3,"b":[7,{"x":1,"y":2,"z":3},1],"c":1}'

// -> formatted: { a: 3, b: [7, { x: 1, y: 2, z: 3 }, 1], c: 1 }
```
