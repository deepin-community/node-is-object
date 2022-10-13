# Installation
> `npm install --save @types/is-object`

# Summary
This package contains type definitions for is-object (https://github.com/ljharb/is-object).

# Details
Files were exported from https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/is-object.
## [index.d.ts](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/is-object/index.d.ts)
````ts
// Type definitions for is-object 1.0
// Project: https://github.com/ljharb/is-object
// Definitions by: Wilson Hobbs <https://github.com/wbhob>
//                 Jordan Harband <https://github.com/ljharb>
//                 Minh-Phuc Tran <https://github.com/phuctm97>
// Definitions: https://github.com/DefinitelyTyped/DefinitelyTyped

export = isObject;

declare function isObject(value: unknown): value is Record<string | symbol | number, unknown>;

declare namespace isObject { }

````

### Additional Details
 * Last updated: Sat, 10 Jul 2021 15:31:15 GMT
 * Dependencies: none
 * Global values: none

# Credits
These definitions were written by [Wilson Hobbs](https://github.com/wbhob), [Jordan Harband](https://github.com/ljharb), and [Minh-Phuc Tran](https://github.com/phuctm97).
