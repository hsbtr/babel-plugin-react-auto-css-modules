# babel-plugin-react-auto-css-modules

Then create-react-app scaffolding can automatically identify css modules

## Example

**In**

```js
// input code
```

**Out**

```js
"use strict";

// output code
```

## Installation

```sh
$ npm install babel-plugin-react-auto-css-modules
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["react-auto-css-modules"]
}
```

### Via CLI

```sh
$ babel --plugins react-auto-css-modules script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["react-auto-css-modules"]
});
```
