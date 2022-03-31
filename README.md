# Myjam Node.js TSConfig Base

This is a TSConfig that is used as a base for Myjam Node.js projects `tsconfig.json` files.  
The config file extends the Node.js LTS release [TSConfig base](https://www.npmjs.com/package/@tsconfig/node12).

## Requirements

- Node.js 14.
- TypeScript 4.4 or higher.

## Installation

Add the package to `package.json` file `devDependencies`.

#### npm
```shell
npm i --save-dev https://git@github.com/my-jam-store/node-tsconfig
```

#### Yarn
```shell
yarn add --dev my-jam-store/node-tsconfig
```

## Usage

Extend the TSConfig base in `tsconfig.json` file.

```json
"extends": "@myjam/node-tsconfig/tsconfig.json"
```

For more details about TSConfig bases, click [here](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html#tsconfig-bases).
