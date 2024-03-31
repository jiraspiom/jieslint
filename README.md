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
npm i -D eslint @jieslint/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@jieslint/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @jieslint/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@jieslint/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @jieslint/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@jieslint/eslint-config/node"
}
```

# create npm package
- [] yarn link
- [] npm login
- [] npm init --scope@jieslint
- [] npm publish