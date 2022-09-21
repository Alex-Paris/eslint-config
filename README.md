# Ghost ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Import Helpers plugin;
- Prettier;

## Setup

1. Install the dependencies
```
npm i -D eslint @ghost-code/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@ghost-code/eslint-config/react"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
