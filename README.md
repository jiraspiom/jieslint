# Rocketseat ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @geslint-config/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@geslint-config/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @geslint-config/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@geslint-config/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @geslint-config/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@geslint-config/eslint-config/node"
}
```

# create npm package
- [] yarn link
- [] npm login
- [] npm init --scope@geslint-config
- [] npm publish