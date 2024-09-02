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

## Documentation

- [What is a tsconfig.json ?](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)
- [TSConfig Reference](https://www.typescriptlang.org/tsconfig/)
- [Compiler Options](https://github.com/microsoft/TypeScript-Website/blob/v2/packages/documentation/copy/en/project-config/Compiler%20Options.md)
- [Compiler Options (archive)](https://github.com/Microsoft/TypeScript-Handbook/blob/master/pages/Compiler%20Options.md)
- [Modules - Choosing Compiler Options](https://www.typescriptlang.org/docs/handbook/modules/guides/choosing-compiler-options.html)
