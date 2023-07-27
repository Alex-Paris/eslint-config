# Paristech ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Import Helpers plugin;
- Automatic tailwind class sorting;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @paristech/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@paristech/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @paristech/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@paristech/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @paristech/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@paristech/eslint-config/node"
}
```