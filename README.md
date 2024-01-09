# React Shopping Cart

A fully functional shopping cart that utilizes local storage.

## Description

I wanted to build out a functional shopping cart that includes adding and removing items from the cart as well as calculating the subtotal of all items. All of this is accomplished using TypeScript, React, JSON data for the custom store items, and local storage.

## Getting Started

### Dependencies

- TypeScript 5.3.3
- React 18.2.0

## Expanding the ESLint configuration

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
    project: ["./tsconfig.json", "./tsconfig.node.json"],
    tsconfigRootDir: __dirname,
  },
};
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
