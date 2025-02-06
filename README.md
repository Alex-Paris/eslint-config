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
Inside `eslint.config.js`
```
import paristechConfig from "@paristech/eslint-config/next";

export default [...paristechConfig]
```
(Optional) For a better experience using Import Helpers you can change the path in `tsconfig.json`. This will let the configured path bellow paths components
```
"paths": {
  "~/*": ["./*"]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @paristech/eslint-config
```
Inside `eslint.config.js`
```
import paristechConfig from "@paristech/eslint-config/react";

export default [...paristechConfig]
```
(Optional) For a better experience using Import Helpers you can change the path in `tsconfig.json`. This will let the configured path bellow paths components
```
"paths": {
  "~/*": ["./*"]
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @paristech/eslint-config
```
Inside `eslint.config.js`
```
import paristechConfig from "@paristech/eslint-config/node";

export default [...paristechConfig]
}
```
(Optional) For a better experience using Import Helpers you can change the path in `tsconfig.json`. This will let the configured path bellow paths components
```
"paths": {
  "~/*": ["./*"]
}
```