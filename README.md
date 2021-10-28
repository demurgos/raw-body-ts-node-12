# Reproduction repo for `raw-body` with `node12` module resolution

```
yarn install
yarn build
```

```
main.mts:1:21 - error TS2307: Cannot find module 'raw-body' or its corresponding type declarations.

1 import rawBody from "raw-body";
                      ~~~~~~~~~~


Found 1 error.
```
