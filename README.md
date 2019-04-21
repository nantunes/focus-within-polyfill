# :focus-within Pseudo-Class Polyfill

[![Build Status](https://travis-ci.org/matteobad/focus-within-polyfill.svg?branch=master)](https://travis-ci.org/matteobad/focus-within-polyfill/)

-   [How to use](#hot-to-use)
-   [Browser support](#browser-support)
-   [:focus-within MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-within)

The `:focus-within` CSS pseudo-class represents an element that has received focus or contains an element that has received focus. In other words, it represents an element that is itself matched by the :focus pseudo-class or has a descendant that is matched by :focus.

More information on [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-within).

## How to use

This package is available both as production ready script and as a package. The script can be downloaded here, or install the package as follow.

```bash
# npm
npm install focus-within-polyfill --save

# yarn
yarn add focus-within-polyfill
```

When the polyfill is included via a script tag it will run immediately after load. On the other hand when imported as a dependency, a call to `polyfill` method is required.

```javascript
import focuswithin from "focus-within-polyfill";

// kick off!
focuswithin.polyfill();
```

## Browser Support

-   _Natively supported in Chrome_
-   _Natively supported in Firefox_
-   _Natively supported in Safari_
-   _Natively supported in Opera_
-   IE 11
-   Edge

## TODO

-   [ ] Write some tests and examples
-   [ ] Publish on npm
