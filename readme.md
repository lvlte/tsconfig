# tsconfig

> Typescript base config for my projects *(requires TypeScript >= 5.5)*

## Install

```sh
npm install --save-dev @lvlte/tsconfig
```

## Usage

In `tsconfig.json` use `extends` and override as needed, eg. :

```json
{
  "extends": "@lvlte/tsconfig",
  "compilerOptions": {
    "target": "ES2024",
  },
  "include": [
    "sources",
    "test"
  ],
  "exclude": ["**/*.spec.ts"]
}
```
