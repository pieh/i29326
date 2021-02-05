Reproduction for https://github.com/gatsbyjs/gatsby/issues/29326

Steps:

```
yarn
gatsby build
```

Result:

```
 ERROR #98123  WEBPACK

Generating SSR bundle failed

/Users/misiek/test/i29326_2/src/pages/index.js: It's not possible to compile spread arguments in
`super()` without compiling classes.
Please add '@babel/plugin-transform-classes' to your Babel configuration. (This is an error on an
internal node. Probably an internal error.)

File: src/pages/index.js

not finished Building HTML renderer - 0.611s
```
