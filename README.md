# css-module-flow
A flow-friendly module that represents a CSS module.

## Installation

```
npm install css-module-flow
```

## Usage

This is not intended to be imported into any project, but instead referenced in one's `.flowconfig` file.

```
[options]
module.name_mapper='^.*\.css$' -> 'css-module-flow'
```

This can be used with any CSS module format such as `.scss`, `.sass`, or `.pcss`

The type `CSSModule` is also exported and can be imported like so:

```js
// @flow
import type { CSSModule } from 'css-module-flow';
```
