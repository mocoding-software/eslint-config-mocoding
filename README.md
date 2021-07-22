# eslint-config-mocoding

> Shared eslint and prettier configuration

The package contains shared [eslint](https://eslint.org/) and [prettier](https://prettier.io/) settings configured to work together for [Typescript](https://www.typescriptlang.org/) and [React](https://reactjs.org/).

## Getting started

Install package as development dependency:

```sh
yarn add --dev eslint-config-mocoding
```

Add the following to lines to `package.json` file:
```json
  "eslintConfig": {
    "extends": "mocoding"
  },
  "prettier": "eslint-config-mocoding/prettier"
```

## Details

Several important notes:
1. `react/prop-types` is disabled. It does not required for Typescript
2. `@typescript-eslint/explicit-function-return-type` changed to `warn` and `allowExpressions` is set to true.


