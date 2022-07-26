# Error in consumer:

```
Uncaught TypeError: (0 , _react.styled) is not a function
    at ./node_modules/@groundgametexas/react/lib-esm/Box.js (Box.js:13:1)
    at options.factory (react refresh:6:1)
    at __webpack_require__ (bootstrap:24:1)
    at fn (hot module replacement:62:1)
    at ./node_modules/@groundgametexas/react/lib-esm/index.js (index.js:23:1)
    at options.factory (react refresh:6:1)
    at __webpack_require__ (bootstrap:24:1)
    at fn (hot module replacement:62:1)
    at ./src/App.js (logo.svg:39:1)
    at options.factory (react refresh:6:1)
```

#### To reproduce

1. `yarn build`
2. symlink and install in a fresh CRA app
3. observe error in consumer
