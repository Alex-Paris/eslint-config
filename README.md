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
(Optional) For a better experience using Import Helpers you can change the path in `tsconfig.json`. This will let the configured path bellow paths components
```
"paths": {
  "@root/*": ["./app/*"]
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
(Optional) For a better experience using Import Helpers you can change the path in `tsconfig.json`. This will let the configured path bellow paths components
```
"paths": {
  "@root/*": ["./src/*"]
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
(Optional) For a better experience using Import Helpers you can change the path in `tsconfig.json`. This will let the configured path bellow paths components
```
"paths": {
  "@root/*": ["./src/*"]
}
```