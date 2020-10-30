# @validatecl/eslint-config
validatecl ESLint standard configuration.

## Usage
```
npm i -D @validatecl/eslint-config
```

### JavaScript
Extend `@validatecl` in your ESLint config.

#### Example

##### `.eslintrc`:
```json
{
  "extends": ["@validatecl"]
}
```

### TypeScript
Extend `@validatecl/eslint-config/typescript` in your ESLint config.

#### Example

##### `.eslintrc`:
```json
{
  "extends": ["@validatecl/eslint-config/typescript"]
}
```

## Rules
See [`index.js`](./index.js) and [`typescript.js`](./typescript.js) to view all the applied rules.
