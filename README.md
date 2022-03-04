# Myjam Node.js TSConfig Base

This is a TSConfig that is used as a base for Myjam Node.js projects `tsconfig.json` files.  
The config file extends the Node.js active LTS release [TSConfig base](https://www.npmjs.com/package/@tsconfig/node16).

## Installation

Add the package to `package.json` file `devDependencies`.

```shell
npm i --save-dev https://git@github.com/my-jam-store/node-tsconfig
```

## Usage

Extend the TSConfig base in `tsconfig.json` file.

```json
{
  "extends": "@myjam/node-tsconfig/tsconfig.json"
}
```

For more details about TSConfig bases, click [here](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html#tsconfig-bases).
